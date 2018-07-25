<template>
  <div id="profile">
    <Me></Me>
  </div>
</template>

<script>
import Me from "@/components/small/Me"
export default {
  components: {
    Me
  }
}
</script>

<style lang="less" scoped>
@width: 100%;
@heigth: 100%;
#profile {
  display: flex;
  justify-content: center;
  align-content: center;
  width: @width;
  height: @heigth;
}
</style>
