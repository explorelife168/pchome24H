<template>
  <div class="main3">
    <div class="main3-btn">
      <ul>
        <li><a href="#">3C</a></li>
        <li><a href="#">周邊</a></li>
        <li><a href="#">NB</a></li>
        <li><a href="#">通訊</a></li>
        <li><a href="#">數位</a></li>
        <li><a href="#">家電</a></li>
        <li><a href="#">日用</a></li>
        <li><a href="#">母嬰</a></li>
        <li><a href="#">食品</a></li>
        <li><a href="#">生活</a></li>
        <li><a href="#">休閒</a></li>
        <li><a href="#">保健</a></li>
        <li><a href="#">美妝</a></li>
        <li><a href="#">時尚</a></li>
        <li><a href="#">居家</a></li>
        <li><a href="#">書店</a></li>
        <li><a href="#">比比昂代購</a></li>
        <li><a href="#">生鮮</a></li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "Main3Component",
};
</script>

<style lang="scss" scoped>
* {
  padding: 0;
  box-sizing: border-box;
  margin: 0;
}

.main3 {
  height: 100px;
  overflow: hidden;
  background-color: #eee;
  float: none;
  margin-left: auto;
  margin-right: auto;
  z-index: 1;

  .main3-btn {
    margin: 8px 0;
    padding: 8px 8px 2px 8px;
    overflow: hidden;
    background-color: #fff;
    cursor: grab;
    ul {
      width: 860px;
      transition-timing-function: ease-out;
      transform: translate3d(0px, 0px, 0px);
      transition-duration: 0ms;

      li {
        list-style: none;
        float: left;
        margin: 0 3px 6px 3px;
        width: 80px;
        border: 1px solid #e3e3e3;
        border-radius: 5px;
        text-align: center;
        a {
          text-decoration: none;
          display: block;
          margin: 0 auto;
          padding: 8px 0;
          color: #666;
          font-size: 13px;
          line-height: 1;
          font-family: Verdana, Geneva, Tahoma, sans-serif;
        }
      }
    }
  }
}
</style>
