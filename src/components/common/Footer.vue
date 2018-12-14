<template>
  <div class="footer">
    <div class="section">
      <div>Услуги</div>
      <a href="#">Хостинг</a>
      <a href="#">Домены</a>
      <a href="#">Аренда ПО</a>
      <a href="#">Почта</a>
    </div>
    <div class="section">
      <div>Компания</div>
      <a href="#">О компании</a>
      <a href="#">Документы</a>
      <a href="#">Операторам связи</a>
    </div>
    <div class="section">
      <div>События</div>
      <a href="#">Новости</a>
      <a href="#">Акции</a>
    </div>
    <div class="section">
      <div>Помощь</div>
      <a href="#">Техническая поддержка</a>
      <a href="#">Оплата</a>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.footer {
  background: rgba(20, 20, 20, 0.5);
  display: flex;
  justify-content: space-between;
  padding: 30px;
}

.section {
  color: #fff;
  display: flex;
  flex: 1;
  flex-direction: column;
  font-size: 14px;
  margin-right: 100px;

  &:last-child {
    margin: 0;
  }

  div {
    font-weight: 600;
    margin-bottom: 10px;
    padding-bottom: 10px;
  }

  a {
    color: #aaa;
    font-size: 12px;
    line-height: 20px;
    text-decoration: none;
  }
}
</style>