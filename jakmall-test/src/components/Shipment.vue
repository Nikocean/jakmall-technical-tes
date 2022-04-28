<template>
  <div>
    <div class="shipment-container">
      <p class="shipment-title">Shipment</p>
      <div class="shipment-detail">
        <input type="text" class="gosend" placeholder="GO-SEND" />
        <input type="text" class="jne" placeholder="JNE" />
        <input
          type="text"
          class="personal-courier"
          placeholder="Personal Courier"
        />
      </div>
    </div>
  </div>
</template>

<style scoped>
input {
  width: 180px;
  height: 60px;
  margin-right: 10px;
}

.shipment-container .shipment-title {
  color: #ff8a00;
  font-size: 36px;
}
</style>

<script>
export default {
  data() {
    return {
      msg: "asdasd",
    };
  },
};
</script>
