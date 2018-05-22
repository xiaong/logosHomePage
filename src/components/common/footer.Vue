<template>
  <div id="appFooter">
    <img src="../../assets/mini_dark_logo.png">Fast Coder © 2017 Fire Cloud Technology
  </div>
</template>

<script>
export default {
  name: 'appFooter'
}
</script>

<style lang="scss">
#appFooter {
  position: relative;
  background-color: #f5f6f5;
  border-top: 1px solid #ebebeb;
  height: 20px;
  line-height: 20px;
  text-align: center;
  font-size: 12px;
  color: #999;
  z-index: 6;

  img {
    display: inline-block;
    width: 15px;
  }
}
</style>
