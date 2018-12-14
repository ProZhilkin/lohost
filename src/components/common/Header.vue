<template>
  <div class="header">
    <div class="logo">
      <img src="@/assets/images/logo.png">
    </div>
    <div class="menu">
      <a href="#">Услуги</a>
      <a href="#">Компания</a>
      <a href="#">Помощь</a>
      <a href="#">Контакты</a>
    </div>
    <div class="phone">
      <i class="fas fa-phone"></i>
      +7 918-148-82-28
    </div>
    <div class="basket">
      <i class="fas fa-shopping-basket"></i>
    </div>
  </div>
</template>

<style lang="scss">
.header {
  display: flex;
  justify-content: space-between;
  padding: 0 30px 0 30px;

  .menu {
    display:flex;
    font-size: 25px;
    font-weight: 300;

    a {
      align-items: center;
      border-top: 5px solid transparent;
      color: #fff;
      display: flex;
      flex: 1;
      margin-right: 20px;
      padding: 10px 0 10px 0;
      text-decoration: none;
    }

    a:hover {
      border-color: #fff;
    }

    a:last-child {
      margin: 0;
    }
  }

  .phone, .basket{
    align-items: center;
    color: #fff;
    display: flex;
  }
}

</style>