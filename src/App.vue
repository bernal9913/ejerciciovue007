<template>
  <div>
    <h1>Mi Lista de Compras</h1>
    <shopping-list :shopping-items="items" />
  </div>
</template>

<script>
import ShoppingList from './components/ShoppingList.vue';

export default {
  data() {
    return {
      items: ['Nutella', 'Huevos kinder', 'MAndarinas', 'un seisillo'],
    };
  },
  components: {
    ShoppingList,
  },
};
</script>
