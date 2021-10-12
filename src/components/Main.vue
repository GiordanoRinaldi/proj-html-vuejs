<template>
  <main>
    <section>
      <div class="d-flex align-items-center subtitle">
        <h4 class="secondFont">OUR CONSULTANS CAN HELP YOU</h4><div class="line"></div>
      </div>
      <div class="row row-cols-2 first-section m-auto">
        <div class="sector">
        <div class="img">
          <img src="../assets/img/line-graph.svg" alt="line graph">
        </div>
        <div class="text">
          <h5>STATISTICAL CONSULTING</h5>
          <div>
            When, while lovely valley teems with vapoure around meand eridian sun strikes the upper impenetrable foliage of my trees, and but a
          </div>
        </div>
      </div>
      <div class="sector ">
        <div class="img">
          <img src="../assets/img/shout.svg" alt="line graph">
        </div>
        <div class="text">
          <h5>DIGITAL CONSULTING</h5>
          <div>
            When, while lovely valley teems with vapoure around meand eridian sun strikes the upper impenetrable foliage of my trees, and but a
          </div>
        </div>
      </div>
      <div class="sector ">
          <div class="img">
            <img src="../assets/img/Path-13.svg" alt="line graph">
          </div>
          <div class="text">
            <h5>BANKING CONSULTING</h5>
            <div>
              When, while lovely valley teems with vapoure around meand eridian sun strikes the upper impenetrable foliage of my trees, and but a
            </div>
          </div>
      </div>
      <div class="sector ">
          <div class="img">
            <img src="../assets/img/target.svg" alt="line graph">
          </div>
          <div class="text">
            <h5>ENTERPRISE CONSULTING</h5>
            <div>
              When, while lovely valley teems with vapoure around meand eridian sun strikes the upper impenetrable foliage of my trees, and but a
            </div>
          </div>
      </div>
      </div>
    </section>
  </main>
</template>

<script>
export default {
    name: "Main"

}
</script>

<style lang="scss" scoped>
@import "../assets/style/common";
  .first-section{
    position: relative;
    color: $principalBackground;
    width: 1200px;
    .sector {
    display: flex;
    margin-bottom: 150px;
    .text {
    width: 350px;
    }
    .img {
    width: 65px;
    height: 65px;
    border-radius: 50%;
    background-color: #f81e3a;
    margin-right: 50px;
      img {
        display: block;
        margin: auto;
        padding-top: 25%;
      }
    }
    }
  }
  .subtitle {
    color: $principalBackground;
    margin: 130px 0 150px 350px;

    .line{
      position: relative;
      width: 71.8%;
      margin-left: 40px;
      margin-right: 0;
    }
  }
  
  
</style>