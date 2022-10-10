<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <BarraLateral/>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import BarraLateral from '@/components/BarraLateral.vue';

export default defineComponent({
  name: 'BarraLateral',
  components: {
    BarraLateral
},
});
</script>
