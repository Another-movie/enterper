<template>
  <div class="header">
    <div class="header__left">
      <div class="tutor">Tutorgo</div>
      <ul>
        <li>Найти учителя</li>
        <li>Стать преподавателем</li>
      </ul>
    </div>
    <div class="header__right">
      <img style='width: 32px' src='@/assets/msg.svg' alt=''>
      <img style='width: 32px' src='@/assets/heart.svg' alt=''>
      <div style='display: flex; align-items: center'>
        <img style="width: 32px; height: auto; border-radius: 16px; margin-right: 8px" src="https://petsworlds.ru/images/sampledata/Profile_avatar_placeholder_large.png" alt=''>
        Жанар Маратова
        <img style='margin-left: 8px; width: 32px' src="@/assets/dropdown.svg" alt=''>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.header {
  width: 80%;
  margin: 0 auto;
  padding: 28px 0;
  display: flex;
  align-items: center;
  justify-content: space-between;

  &__left {
    display: flex;
    align-items: center;

    ul {
      display: flex;
      align-items: center;
      text-decoration: none;
      list-style: none;

      li {
        margin-right: 32px;
      }
    }
  }

  &__right {
    display: flex;
    align-items: center;

    & > img {
      margin-right: 32px !important;
    }


  }
}
.tutor {
  font-style: normal;
  font-weight: bold;
  font-size: 24px;
  line-height: 24px;
  margin-right: 64px;
  display: flex;
  align-items: center;
  text-transform: uppercase;
  color: #08033a;
}
</style>
