<script setup>
import { useCounterStore } from "../stores/useCounterStore";
const store = useCounterStore();
</script>

<template>
  <div class="text-3xl">
    <p>Home</p>
    <p>{{ store.count }}</p>
  </div>
</template>
