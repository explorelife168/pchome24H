<template>
  <div class="main2">
    <div class="title">
      <div class="clock">
        <i class="fa-solid fa-clock"></i>
        <span>限時瘋搶</span>
        <span>每日10點開搶</span>
      </div>
      <a href="#">看更多></a>
    </div>
    <div class="pic-change">
      <div class="pic-txt-1">
        <div class="txt-1">
          <p>限時瘋搶<span>10:00</span>現正瘋搶</p>
        </div>
        <div class="pic-1">
          <img src="../assets/main2-1.jpeg" alt="" />
        </div>
      </div>
      <div class="pic-txt-2">
        <div class="txt-2">
          <p>限時瘋搶<span>10:00</span>現正瘋搶</p>
        </div>
        <div class="pic-2">
          <img src="../assets/main-2-2.webp" alt="" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Main2Component",
};
</script>

<style lang="scss" scoped>
* {
  padding: 0;
  box-sizing: border-box;
  margin: 0;
}
.main2 {
  width: 100%;
  display: flex;
  flex-direction: column;
  margin-bottom: 8px;
  .title {
    display: flex;
    width: 100%;
    height: 40px;
    justify-content: space-between;
    align-items: center;
    background-color: #ea1717;
    padding: 0 16px 0 20px;
    .clock {
      width: 214.58px;
      display: flex;
      align-items: center;
      span {
        margin-right: 8px;
        color: #fff;
      }
      :nth-child(1) {
        margin-right: 8px;
        color: white;
      }
      :nth-child(2) {
        font-size: 20px;
      }
      :nth-child(3) {
        font-size: 14px;
      }
    }
    a {
      text-decoration: none;
      color: white;
      font-size: 13px;
    }
  }
  .pic-change {
    display: flex;
    width: 100%;
    height: 100%;
    .pic-txt-1 {
      width: 50%;
      border: 1px solid #eee;
      margin-right: 4px;
      .txt-1 {
        p {
          height: 32px;
          color: #414141;
          font-size: 14px;
          font-weight: 500;
          line-height: 14px;
          font-family: Verdana, Geneva, Tahoma, sans-serif;
          background-color: #f2f2f2;
          text-align: center;
          line-height: 32px;

          span {
            font-size: 16px;
            margin: 0 4px;
            color: #ea1717;
            font-weight: 700;
          }
        }
      }
      .pic-1 {
        img {
          width: 100%;
        }
      }
    }
    .pic-txt-2 {
      width: 50%;
      border: 1px solid #eee;
      margin-right: 4px;
      .txt-2 {
        p {
          height: 32px;
          color: #414141;
          font-size: 14px;
          font-weight: 500;
          line-height: 14px;
          font-family: Verdana, Geneva, Tahoma, sans-serif;
          background-color: #f2f2f2;
          text-align: center;
          line-height: 32px;
          span {
            font-size: 16px;
            margin: 0 4px;
            color: #ea1717;
            font-weight: 700;
          }
        }
      }
      .pic-2 {
        img {
          width: 100%;
        }
      }
    }
  }
}
</style>
