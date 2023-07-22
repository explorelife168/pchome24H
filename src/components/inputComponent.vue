<template>
  <div>
    <div class="input-all">
      <div class="input">
        <input type="search" class="text" placeholder="芭比" />
        <span class="b-search">找商品</span>
      </div>
    </div>
    <div class="pic-1">
      <img src="../assets/pic-1.jpeg" alt="" />
    </div>
  </div>
</template>

<script>
export default {
  name: "inputComponent",
};
</script>

<style lang="scss" scoped>
* {
  padding: 0;
  box-sizing: border-box;
  margin: 0;
}

.input-all {
  margin: 10px 10px 15px 10px;
  position: relative;
  .input {
    height: 37px;
    border: 1px solid #0141ad;
    border-radius: 3px;
    box-shadow: 3px 3px 0 #d3d3d3;
    background-color: #fff;
    input {
      padding: 0 0 0 10px;
      width: 100%;
      height: 35px;
      border: 0;
      color: #333;
      font-size: 16px;
      background: 0;
    }
    .b-search {
      position: absolute;
      top: 0;
      right: 0;
      text-align: center;
      width: 83px;
      height: 36px;
      font-weight: bold;
      font-size: 18px;
      line-height: 36px;
      font-family: Arial;
      border-radius: 0 4px 4px 0;
      border: 1px solid #005cb8;
      color: #fff;
      background: #0087f5;
      box-shadow: 0 0 6px #0042ac inset;
      cursor: pointer;
    }
  }
}
.pic-1 {
  max-width: 100%;
  max-height: auto;
  img {
    width: 100%;
    height: 100%;
  }
}
</style>
