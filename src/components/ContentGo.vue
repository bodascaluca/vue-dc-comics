<template>
  <div>
    <div class="back-cl">
      <div class="container">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ContentGo",
};
</script>

<style scoped lang="scss">
@import "../style/common.scss";

.back-cl {
  background-image: url("../assets/img/jumbotron.jpg");
  height: 200px;
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-position: center top;
  background-size:cover;

  .container {
    width: 80%;
    margin: 0 auto;
    height:200px;
  }
}
</style>
