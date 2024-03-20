<script setup>
function tonovai(event) {
  if (event) {
    location.replace("https://novelai.net");
  }
}

function toaid(event) {
  if (event) {
    location.replace("https://play.aidungeon.io");
  }
}
</script>

<template>
  <div class="container">
    <h1>Choose your Adventure</h1>

    <div class="row">
      <button class="btn" @click="tonovai"><img src="./assets/novelai_light.png" class="logo novelai"
          alt="Vite logo" /></button>
      <button class="btn" @click="toaid"><img src="./assets/aid_light.svg" class="logo aid" alt="Vue logo" /></button>
    </div>
  </div>
</template>

<style scoped>
.logo.novelai:hover {
  filter: drop-shadow(0 0 2em #747bff);
}

.logo.aid:hover {
  filter: drop-shadow(0 0 2em #249b73);
}
</style>
