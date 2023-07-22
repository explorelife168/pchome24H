<template>
  <div>
    <div class="nav">
      <div class="top-menu">
        <div class="side-menu">
          <i class="fa-solid fa-bars fa-2x" style="color: #dd0000"></i>
        </div>
        <div class="logo">
          <img src="../assets/pchomelogo.png" alt="" />
        </div>
        <div class="cart">
          <div class="cart-img">
            <i
              class="fa-solid fa-cart-shopping fa-2x"
              style="color: #dd0000"
            ></i>
          </div>
          <div class="quantity">
            <p>(0)</p>
          </div>
        </div>
      </div>
      <div class="down-menu">
        <div class="menu">
          <ul>
            <li><a href="#">首頁</a></li>
            <li><a href="#">限時瘋搶</a></li>
            <li><a href="#">每日特賣</a></li>
            <li><a href="#">影音專區</a></li>
            <li><a href="#">強檔活動</a></li>
            <li><a href="#">智慧標籤</a></li>
          </ul>
        </div>
      </div>
    </div>
    <div class="fixed"></div>
  </div>
</template>

<script>
export default {
  name: "NavComponent",
};
</script>

<style lang="scss" scoped>
* {
  padding: 0;
  box-sizing: border-box;
  margin: 0;
}

.nav {
  width: 100%;
  height: 75px;
  display: flex;
  flex-direction: column;
  position: fixed;
  z-index: 10;
  background-color: white;

  .top-menu {
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 100%;
    height: 38px;
    border-bottom: 2px solid #d00;
    .side-menu {
      margin: 12px;
    }
    .logo {
      width: 162px;
      img {
        width: 100%;
        height: 100%;
      }
    }
    .cart {
      display: flex;
      align-items: center;
      height: 38px;
      margin: 12px;
      .quantity {
        P {
          color: #dd0000;
        }
      }
    }
  }
  .down-menu {
    width: 100%;
    height: 37px;
    border-bottom: 1px solid #eee;
    .menu {
      ul {
        display: flex;
        align-items: center;
        height: 37px;

        li {
          font-size: 15px;
          padding: 0 7px;
          list-style: none;

          a {
            color: #333333;
            text-decoration: none;
            height: 37px;
          }
          a:hover {
            color: #dd0000;
          }
        }
      }
    }
  }
}
.fixed {
  width: 575px;
  height: 75px;
}
</style>
