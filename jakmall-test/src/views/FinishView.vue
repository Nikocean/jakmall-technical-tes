<script setup>
import Summary from '@/components/Summary.vue';
</script>

<template>
  <div class="finish">
    <div class="body">
      <p>Thank you</p>
    </div>

    <Summary />
  </div>
</template>

<style>
.finish{
  display: flex;
}

.body{
  margin-right: 30px;
}

@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>