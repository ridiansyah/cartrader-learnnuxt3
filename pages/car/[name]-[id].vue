<script setup>
const route = useRoute();
const { cars } = useCars();
const { toTitleCase } = useUtilities();

useHead({
  title: toTitleCase(route.params.name),
});
definePageMeta({
  layout: "custom",
});
const car = computed(() => {
  return cars.find((obj) => {
    return obj.id === parseInt(route.params.id);
  });
});
</script>
<template>
  <div v-if="car">
    <CarDetailHero :car="car" />
    <CarDetailAttributes :features="car?.features" />
    <CarDetailDescription :description="car?.description" />
    <CarDetailContact />
  </div>
</template>
