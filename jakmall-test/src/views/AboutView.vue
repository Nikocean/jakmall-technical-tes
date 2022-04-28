<script setup>
import Shipment from '@/components/Shipment.vue';
import Payment from '@/components/Payment.vue';
import Summary from '@/components/Summary.vue';
</script>

<template>
  <div class="about">
    <div class="body">
      <Shipment />
      <Payment />
    </div>

    <Summary />
  </div>
</template>

<style>
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

