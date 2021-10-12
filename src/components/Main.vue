<template>
  <main>
    <section class="row">
      <div class="col-12">
        <h4 class="secondFont">OUR CONSULTANS CAN HELP YOU</h4><div class="line"></div>
      </div>
      <div class="sector d-flex col">
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
      <div class="sector d-flex col">
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
  section{
    color: $principalBackground;
  }

  .img {
    width: 65px;
    height: 65px;
    border-radius: 50%;
    background-color: #f81e3a;

    img {
      display: block;
      margin: auto;
      padding-top: 25%;
    }
  }
</style>