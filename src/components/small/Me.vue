<template>
  <div id="my-picture">
    <div class="oval">
      <img src="https://openclipart.org/image/2400px/svg_to_png/102217/jphead.png" alt="my-picture" id="picutre">
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="less" scoped>
@width: 100%;
@height: 100%;
#my-picture {
  display: flex;
  justify-content: center;
  width: @width;
  height: @height;
}
.oval {
  display: flex;
  height: 250px;
  width: 250px;
  border-radius: 50%;
  background-color: #dedede;
  border: 1px solid;
  border-top-color: red;
  border-bottom-color: red;
  justify-content: center;
  align-items: center;
}

img#picutre {
  height: 130px;
}
</style>
