<template>
  <div>
    <div class="payment-container">
      <p class="payment-title">Payment</p>
      <div class="payment-detail">
        <input type="text" class="ewallet" placeholder="e-Wallet" />
        <input type="text" class="bank-transfer" placeholder="Bank Transfer" />
        <input
          type="text"
          class="virtual-account"
          placeholder="Virtual Account"
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

.payment-container .payment-title {
  color: #ff8a00;
  font-size: 36px;
}
</style>
