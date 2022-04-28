<template>
  <div class="summary">
    <header>
      <p class="title">Summary</p>
    </header>

    <div class="body">
      <p>10 items purchased</p>

      <div class="items">
        <div class="item">
          <p>Cost of Goods</p>
          <p>500,000</p>
        </div>
        <div class="item">
          <p>Dropshipper fee</p>
          <p>5,900</p>
        </div>
      </div>

      <button class="ctn-payment">Continue to Payment</button>
    </div>
    
  </div>
</template>

<style scoped>
.summary {
  width: 300px;
  height: 500px;
  border-left: 1px solid #ff8a00;
  padding: 30px 0 10px 30px;
}

.title{
  color: #FF8A00;
  font-size: 24px;
  font-weight: 700;
}

.items{
  margin-top: 205px;
}

.items .item {
  display: flex;
  justify-content: space-between;
}

.body .ctn-payment{
  background: #FF8A00;
  color: white;
  width: 260px;
  height: 60px;
  border-style: none;
}
</style>
