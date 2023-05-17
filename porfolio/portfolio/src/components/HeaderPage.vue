<template>
  <div class="header">
    <!-- titolo e immagine -->
    <div class="main-header">
      <div class="navbar">
        <!-- neon  -->
        <div class="container">
          <div class="row">
            <div class="col-md-12 text-center">
              <h3 class="animate-charcter">Full Stack Web Developer</h3>
            </div>
          </div>
        </div>
        <!-- <h3>Junior Full Stack Web Developer</h3> -->
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
  text-align: center;
  justify-content: center;
}

p {
  font-size: 50%;
  text-align: center;
}

.animate-charcter
{
   text-transform: uppercase;
  background-image: linear-gradient(
    -225deg,
    #231557 0%,
    #44107a 29%,
    #ff1361 67%,
    #fff800 100%
  );
  background-size: auto auto;
  background-clip: border-box;
  background-size: 200% auto;
  color: #fff;
  background-clip: text;
  text-fill-color: transparent;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  animation: textclip 2s linear infinite;
  display: inline-block;
      font-size: 100px;
}

@keyframes textclip {
  to {
    background-position: 200% center;
  }
}
</style>
