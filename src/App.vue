<template>
  <div id="app">
    <div class="section-one">
      <Header/>
      <div class="jumbotron">
        <div class="container-fluid new-container">
          <div class="text-jumbo">
            <div> <span class="line"></span> ALWATS THE BEST WAY YOU NEED IT</div>
            <h1 class="secondFont">THE BEST BUSINESS CONSULTING</h1>
            <div class="buttons d-flex">
              <button class="Primarybutton me-4" >READ MORE</button>
              <button class="playButton align-self-end"><i class="fas fa-caret-right"></i></button>
            </div>
            
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
  @import '~@fortawesome/fontawesome-free/css/all.css';
  #app {
    color: $mainTitlecolor;
    font-family: 'Montserrat', sans-serif;
  }
  .section-one {
    height: 100vh;
    background-color: $principalBackground;
    background-image: url("./assets/img/portrait-of-young-architect-woman-on-meeting-KFZCE3A.jpg");
    background-repeat: no-repeat;
    background-position: right top;

    .text-jumbo {
      margin-top: 200px;
      width: 600px;
    }

    .secondFont{
      font-size: 100px;
    }
  }

  .playButton {
    width: 55px;
    height: 55px;
    border-radius: 50%;
    background-color: transparent;
    border: 2px solid white;
  }

  .fas.fa-caret-right {
    color: $buttonColor;
    font-size: 30px;
  }





</style>
