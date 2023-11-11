<template>
  <div>
    <h2>Lista de Compras</h2>
    <ul>
      <li v-for="item in shoppingItems" :key="item">
        {{ item }}
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  props: {
    shoppingItems: {
      type: Array,
      required: true,
    },
  },
};
</script>
