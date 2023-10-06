<!-- /products/:id -->
<template>
  <div>
    <p>Product details for {{ id }}</p>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Qui consequuntur
      quod, dicta, doloremque impedit facere eum est voluptatem laboriosam,
      libero iure delectus! Illum ea sint quo, facere numquam unde temporibus!
    </p>
  </div>
</template>

<script setup>
const { id } = useRoute().params;

definePageMeta({
  layout: "products",
});
</script>

<style scoped></style>
