<template>
  <div class="blocchi">
    <!-- logo alealle -->
    <HeaderPage></HeaderPage>
    <MainContainer></MainContainer>
    <ProjectPage></ProjectPage>
    <FooterPage></FooterPage>
  </div>
</template>

<script>
import HeaderPage from './components/HeaderPage.vue'
import MainContainer from './components/MainContainer.vue'
import ProjectPage from './components/ProjectPage.vue'
import FooterPage from './components/FooterPage.vue'

export default {
  name: 'App',
  components: {
    HeaderPage,
    MainContainer,
    ProjectPage,
    FooterPage,
  }
}
</script>

<style>
.blocchi {
  font-size: 40px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  gap: 50px;
}
</style>
