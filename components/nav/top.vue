<template>
  <div class="topnav">
    <div class="topnav__linkContent">about</div>
    <div class="topnav__linkContent">ログイン</div>
    <div class="topnav__linkContent">会員登録</div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.topnav {
  background-color: gray;
  color: black;
  display: flex;
  flex-direction: row-reverse;
  height: 3vh;
  &__linkContent {
    margin-right: 1vw;
  }
}
</style>
