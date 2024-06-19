<template>
  <header>
    <div class="topBar">
      <div class="container">
        <div class="tobBarLeft"><a href="#">Become a Seller</a></div>
        <div class="topBarCenter">
          <div><span>Something you love is now on sale <strong><a href="#">Buy Now!</a></strong></span></div>
        </div>
        <div class="topBarRight">
          <span>Turkish</span>
          <span>|</span>
          <span>TL</span>
        </div>
      </div>
    </div>
  </header>
</template>

<script lang="ts" setup>

</script>

<style scoped lang="scss">
.topBar {
  .container {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    flex-wrap: nowrap;
    gap: 20px;
  }

  .topBarRight {
    & span {
      color: $secondary;
    }
  }

}
</style>
