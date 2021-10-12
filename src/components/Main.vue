<template>
  <main>
    <section class="first-section">
      <div class="d-flex align-items-center subtitle">
        <h4 class="secondFont">OUR CONSULTANS CAN HELP YOU</h4><div class="line"></div>
      </div>
      <div class="row row-cols-2 statistics m-auto">
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

    <section class="second-section">
      <div class="d-flex align-items-center">
        <div class="img">
          <img src="../assets/img/business-people-working-together-on-project-and-5FHSKBL.jpg" alt="">
        </div>
        <div class="text">
          <div><span class="line"></span> ABOUT US</div>
          <h2 class="secondFont">WE MAKE YOUR STRATEGY WORK</h2>
          When, while the lovely valley teems with vapour around me, and the meridian sun strikes the upper surface of the impenetrable foliage of my trees, and but a thousand unknown plants are noticed when i hear the buzz of the little world among the stalks, and grow familiar with the countless indescribable forms of the insects and flies, then I feel the presence of the Almighty.
        </div>
      </div>
      <div class="get-started d-flex justify-content-center align-items-center">
        <div class="d-flex">
          <div class="me-5"> <h3 class="secondFont">WE HELP TO DELIVER THE BUSINESS CASE</h3> </div>
          <div class="ms-5">When, while lovely valley teems with vapoure around meand eridian sun strikes the upper impenetrable foliage of my trees, and but a THOUSAND unknown</div>
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
.first-section {
  h5 {
     font-family: 'Bai Jamjuree', sans-serif;
    font-weight: 700;;
  }
  .statistics{
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
}

.second-section {
  background-color: $principalBackground;

  h2{
    font-size:60px;
    margin: 40px 0 40px 0
  }

  .img {
    width: 1070px;

    img {
      width: 100%;
    }
  }

  .text {
    width: 500px;
    margin-left: 90px ;
  }


  .get-started {
    color: $principalBackground;
    height: 330px;
    width: calc(100vw - 10%);
    background-color: #39FFBF;
    div{
      div{
        width: 430px;
      }
    }
  }
}
  
  
  
  
</style>