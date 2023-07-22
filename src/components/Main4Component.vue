<template>
  <div class="main4">
    <div class="title-3c">
      <div class="mb">
        <i class="fa-solid fa-laptop"></i>
        <span>每日特價</span>
        <span>3C數位/手機</span>
      </div>
      <a href="#">看更多></a>
    </div>
    <div class="pic-3c">
      <ul>
        <li><img src="../assets/3c-1.webp" alt="" /></li>
        <li><img src="../assets/3c-2.webp" alt="" /></li>
        <li><img src="../assets/3c-3.webp" alt="" /></li>
        <li><img src="../assets/3c-4.webp" alt="" /></li>
        <li><img src="../assets/3c-5.webp" alt="" /></li>
        <li><img src="../assets/3c-6.webp" alt="" /></li>
        <li><img src="../assets/3c-7.webp" alt="" /></li>
        <li><img src="../assets/3c-8.webp" alt="" /></li>
        <li><img src="../assets/3c-9.webp" alt="" /></li>
        <li><img src="../assets/3c-10.webp" alt="" /></li>
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

.main4 {
  .title-3c {
    display: flex;
    width: 100%;
    height: 40px;
    justify-content: space-between;
    align-items: center;
    background-color: #0090eb;
    padding: 0 16px 0 20px;
    .mb {
      width: 320px;
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
        font-size: 20px;
      }
    }
    a {
      text-decoration: none;
      color: white;
      font-size: 13px;
    }
  }
  .pic-3c {
    width: 100%;
    ul {
      display: flex;
      flex-wrap: wrap;
      li {
        width: 50%;
        padding: 5px;
        border: 1px solid #eee;
        img {
          width: 100%;
        }
      }
    }
  }
}
</style>
