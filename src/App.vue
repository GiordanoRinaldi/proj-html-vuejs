<template>
  <div id="app">
    <div class="section-one">
      <Header/>
      <div class="jumbotron">
        <div class="container-fluid new-container">
          <div class="text-jumbo">
            <div> <span class="line"></span> ALWATS THE BEST WAY YOU NEED IT</div>
            <h1>THE BEST BUSINESS CONSULTING</h1>
            <button >READ MORE</button>
            <button>></button>
          </div>
          
        </div>
      </div>
    </div>
    

  </div>
</template>

<script>
import Header from "./components/Header.vue"

export default {
  name: 'App',
  components: {
    Header,
  }
}
</script>

<style lang="scss">
  @import "./assets/style/common";
  #app {
    color: $mainTitlecolor;
    font-family: 'Montserrat', sans-serif;
  }
  .section-one {
    height: 100vh;
    background-color: $principalBackground;
    background-image: url("./assets/img/portrait-of-young-architect-woman-on-meeting-KFZCE3A.jpg");
    background-repeat: no-repeat;
    background-position: top right;

    .text-jumbo {
      margin-top: 200px;
    }
  }





</style>
