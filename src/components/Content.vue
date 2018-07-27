<template>
  <div class="body">
    <div class="content">
      <div class="left-side">
        <h3>HELLO</h3>
        <div class="greet">
          <p class="left-text">I'm Erwin W. Ramadhan</p>
          <p class="left-text">Software Engineer</p>
          <img class="map" src="https://cdn3.iconfinder.com/data/icons/countries-map/48/Indonesia-512.png" alt="indonesia">
          <p class="left-text">Indonesia</p>
        </div>
      </div>
      <div class="separator">
        <div class="line"></div>
      </div>
      <div class="right-side">
        <h3>CONTACT</h3>
        <div class="detail">
          <p class="right-text">erwinwahyuramadhan@gmail.com</p>
          <p class="right-text">+62 82242361317</p>
          
          <div class="socmed">
            <img class="icon-socmed" src="http://www.stickpng.com/assets/images/58e91afdeb97430e81906504.png" alt="linkedin">
            <a href="https://www.linkedin.com/in/erwinwahyura/">
              <p class="right-text">Erwin W. Ramadhan</p>
            </a>
          </div>

          <div class="socmed">
            <img class="icon-socmed" src="https://image.flaticon.com/icons/svg/25/25231.svg">
            <a href="https://github.com/erwinwahyura/">
              <p class="right-text">erwinwahyura</p>
            </a>
          </div>
          
          <p class="right-text">Indonesia</p>
        </div>
      </div>

      <!-- second row -->

    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="less" scoped>
@width: 100%;
@width-side: 45%;

.body {
  margin: 50px;
  display: flex;
  width: 100%;
}

.content {
  display: flex;
  width: @width;
}
.left-side {
  display: flex;
  width: @width-side;
  // border: 1px solid black;
  justify-content: flex-end;
  flex-wrap: wrap;
}
.separator {
  display: flex;
  width: 10%;
  justify-content: center;
}
.line {
  display: flex;
  width: 1%;
  // border-radius: 30%;
  // background-color: #000;
  border: 5px dotted;
  border-left-color: red;
  border-right-color: black;
}
.right-side {
  display: flex;
  width: @width-side;
  // border: 1px solid red;
  justify-content: flex-start;
  flex-wrap: wrap;
}
// ========== left content ===========
.greet {
  display: flex;
  width: 100%;
  flex-wrap: wrap;
  justify-content: flex-end;
}
.left-text {
  width: @width;
  display: flex;
  justify-content: flex-end;
  margin: 0px;
  flex-wrap: wrap;
}

img.map {
  width: 150px !important;
  height: 90px !important;
}
// ========== left content ===========

// ========== right content ===========
.detail {
  display: flex;
  height: 90%;
  width: 100%;
  flex-wrap: wrap;
  justify-content: flex-start;
  align-content: flex-start;
  line-height: 1.44em;
}

.right-text {
  width: @width;
  display: flex;
  justify-content: flex-start;
  margin: 0px;
}
.socmed {
  display: flex;
  width: @width;
}
.icon-socmed {
  display: flex;
  width: 20px;
  height: 20px;
  margin-right: 5px;
  flex-wrap: wrap;
}
a {
  text-decoration: none;
}
// ========== right content ===========

h3 {
  height: 10%;
}
</style>

