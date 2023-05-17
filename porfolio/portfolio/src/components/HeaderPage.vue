<template>
  <div class="header">
    <!-- titolo e immagine -->
    <div class="main-header">
      <div class="navbar">
        <h3>Junior Full Stack Web Developer</h3>
        <img src="../assets/profilo.jpeg" alt="">
      </div>
      <p>"Coding is a never-ending learning journey, where every line of code is an opportunity to grow</p>
    </div>
  </div>
</template>


<script>
export default {
  name: 'HeaderPage',
}
</script>


<!-- stile -->
<style scoped>
.navbar {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

/* TITOLO JUNIOR  */
h3 {
  background-image: linear-gradient(
    to right,
    #54b3d6,
    #54b3d6 50%,
    #000 50%
  );
  background-size: 200% 100%;
  background-position: -100%;
  display: inline-block;
  padding: 5px 0;
  position: relative;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  transition: all 0.3s ease-in-out;
}
h3:before {
  content: '';
  background: #54b3d6;
  display: block;
  position: absolute;
  bottom: -3px;
  left: 0;
  width: 0;
  height: 3px;
  transition: all 0.3s ease-in-out;
}
h3:hover {
  background-position: 0;
  scale: 1.1;
}
h3:hover::before {
  width:100%;
}
/* FINE TITOLO */

p {
  font-size: 50%;
  text-align: center;
}

img {
  border-radius: 70%;
  height: 70px;
}
</style>
