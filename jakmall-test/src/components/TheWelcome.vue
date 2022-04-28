<template>
  <div class="delivery-details">
    <div class="delivery-detail-title">
      <p class="title">Delivery Detail</p>
      <label for="" class="dropshipper">
        <input type="checkbox" name="" id="" />
        Send as dropshipper
      </label>
    </div>

    <div class="input-detail">
      <div class="input-name">
        <input type="text" class="name" placeholder="Name">
        <input type="text" class="dropshipper" placeholder="Dropshipper Name">
      </div>
      <div class="input-phone">
        <input type="text" class="phone" placeholder="Phone Number">
        <input type="text" class="drophipper-phone" placeholder="Dropshipper phone number">
      </div>
      <div class="input-address">
        <input type="text" class="address" placeholder="Delivery Address">
      </div>
    </div>
  </div>
</template>

<style scoped>
.delivery-details{
  position: relative;
}

.delivery-detail-title .title{
  color: #FF8A00;
  font-size: 36px;
  font-weight: 700;
}

.delivery-detail-title .dropshipper{
  font-size: 14px;
  font-weight: 500;
  margin: auto;
}

.delivery-details .delivery-detail-title{
  display: flex;
}

.input-detail input{
  margin: 10px 30px 0 0;
  border: 1px solid #CCC
}

.input-name .name{
  width: 400px;
  height: 60px;
}

.input-name .dropshipper{
  width: 300px;
  height: 60px;
}

.input-phone .phone{
  width: 400px;
  height: 60px;
}

.input-phone .drophipper-phone{
  width: 300px;
  height: 60px;
}

.input-address .address{
  width: 400px;
  height: 120px;
}

</style>
