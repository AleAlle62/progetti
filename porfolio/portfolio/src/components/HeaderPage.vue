<template>
  <div class="header">
    <!-- titolo e immagine -->
    <div class="main-header">
      <div class="navbar">
        <h3>Junior Full Stack Web Developer</h3>
        <img src="../assets/profilo.jpeg" alt="">
      </div>
      <p>Coding is a never-ending learning journey, where every line of code is an opportunity to grow</p>
    </div>
  </div>
</template>


<script>
export default {
  name: 'HeaderPage',
}
</script>


<style scoped>
.navbar {
  display: flex;
  justify-content: space-around;

}

p {
  font-size: 80%;
}

img {
  border-radius: 70%;
  height: 70px;
}
</style>
