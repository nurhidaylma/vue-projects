<template>
  <div class="logos-wrapper">
    <h2 class="title-header">Find Best Logo</h2>
    <div class="item-logos">
      <img class="logo" src="../assets/gopher.png" alt="Gopher" />
    </div>
    <div class="item-logos">
      <img class="logo" src="../assets/docker.svg" alt="Docker" />
    </div>
    <div class="item-logos">
      <img class="logo" src="../assets/gopher.png" alt="Gopher" />
    </div>
    <div class="item-logos">
      <img class="logo" src="../assets/docker.svg" alt="Docker" />
    </div>
    <div class="item-logos">
      <img class="logo" src="../assets/docker.svg" alt="Docker" />
    </div>
    <div class="item-logos">
      <img class="logo" src="../assets/gopher.png" alt="Gopher" />
    </div>
    <div class="item-logos">
      <img class="logo" src="../assets/docker.svg" alt="Docker" />
    </div>
    <div class="item-logos">
      <img class="logo" src="../assets/gopher.png" alt="Gopher" />
    </div>
  </div>
</template> 

<script>
export default {
  name: "LogosItem",
};
</script>

<style scoped>
.title-header {
  margin-bottom: 80px;
  text-align: left;
  margin-left: 50px;
}

.logos-wrapper {
  width: 70%;
  overflow: hidden;
  margin: auto;
}

.item-logos {
  width: 150px;
  height: 150px;
  float: left;
  margin-left: 50px;
}

.item-logos .logo {
  width: 100px;
  height: 100px;
}
</style>