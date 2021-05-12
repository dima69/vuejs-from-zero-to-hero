<template>
  <header>
    <h1 class="text-center font-semibold text-2xl m-2">
      global navigation menu on: {{ page_title }}
    </h1>
    <nav class="max-w-3xl mx-auto">
      <ul class="flex justify-between font-medium">
        <li class="p-2 bg-indigo-100 hover:underline rounded-xl"><a href="/">menu_item_1</a></li>
        <li class="p-2 bg-indigo-100 hover:underline rounded-xl"><a href="/">menu_item_2</a></li>
        <li class="p-2 bg-indigo-100 hover:underline rounded-xl"><a href="/">menu_item_3</a></li>
        <li class="p-2 bg-indigo-100 hover:underline rounded-xl"><a href="/">menu_item_4</a></li>
        <li class="p-2 bg-indigo-100 hover:underline rounded-xl"><a href="/">menu_item_5</a></li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: "Header",
  props: {
    page_title: String,
  },
};
</script>

<style scoped>
header {
  font-size: large;
  margin-left: auto;
  margin-right: auto;
}
</style>