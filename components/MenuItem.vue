<template>
  <div class="flex mt-5">
    <div class="basis-1/4">
      <img class="rounded-xl" :src="image" alt="" />
    </div>
    <div class="basis-3/4 px-5">
      <h3 class="uppercase text-blue-900 font-bold">{{ name }}</h3>
      <div class="py-2 pr-5">
        {{ description }}
      </div>
      <div class="font-bold">RM {{ price }}</div>
    </div>
  </div>
</template>

<script>
export default {
  props: ["name", "description", "price", "image"],
};
</script>
