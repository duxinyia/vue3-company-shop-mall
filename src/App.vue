<script setup>
import { useCounterStore } from "@/store/counter";
const counterStore = useCounterStore();
console.log(counterStore);
</script>
<template>
  <button>{{ counterStore.count }}</button>
  <!-- <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav>
  <router-view/> -->
</template>

<style lang="less"></style>
