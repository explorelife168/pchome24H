<template>
  <div class="main">
    <ul>
      <li>
        <div class="txt">
          <img src="../assets/main-1.png" />
        </div>
        <p>我的折價券</p>
      </li>
      <li>
        <div class="txt">
          <img src="../assets/main-2.png" />
        </div>
        <p>儲值更划算</p>
      </li>
      <li>
        <div class="txt">
          <img src="../assets/main-3.png" />
        </div>
        <p>Pi卡享6</p>
      </li>
      <li>
        <div class="txt">
          <img src="../assets/main-4.png" />
        </div>
        <p>活動總覽</p>
      </li>
      <li>
        <div class="txt">
          <img src="../assets/main-5.png" />
        </div>
        <p>電競爭霸戰</p>
      </li>
      <li>
        <div class="txt">
          <img src="../assets/main-6.png" />
        </div>
        <p>出遊散策</p>
      </li>
      <li>
        <div class="txt">
          <img src="../assets/main-7.png" />
        </div>
        <p>風扇5折起</p>
      </li>
      <li>
        <div class="txt">
          <img src="../assets/main-8.png" />
        </div>
        <p>刷卡享優惠</p>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "MainComponent",
};
</script>

<style lang="scss" scoped>
* {
  padding: 0;
  box-sizing: border-box;
  margin: 0;
}

.main {
  ul {
    display: flex;
    flex-wrap: wrap;
    padding: 4px;
    margin: 10px 0;
    width: 100%;
    li {
      list-style: none;
      margin: 4px 6px;
      width: calc(100% / 4 - 12px);
      .txt {
        display: flex;
        justify-content: center;
        align-items: center;
        cursor: pointer;
        img {
          max-width: 100%;
          width: 100%;
          height: auto;
        }
      }
      p {
        text-align: center;
        font-size: 13px;
        line-height: 1.2;
        font-family: Verdana, Geneva, Tahoma, sans-serif;
      }
    }
  }
}
</style>
