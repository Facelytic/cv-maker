<template>
  <div id="home">
    <Header></Header>
    <div class="mid">
      <Profile></Profile>
    </div>
   <div class="body">
      <Content></Content>
   </div>
   <div class="body">
      <Content></Content>
   </div>
   <div class="body">
      <Content></Content>
   </div>
  </div>
</template>

<script>
// @ is an alias to /src
import Header from "@/components/Header"
import Profile from "@/components/Profile"
import Content from "@/components/Content"
export default {
  name: "home",
  components: {
    Header,
    Profile,
    Content
  }
}
</script>

<style lang="less" scoped>
#home {
  display: flex;
  width: 100%;
  height: 100%;
  flex-wrap: wrap;
  background-color: #dedede;
  border: 1px solid #dedede;
}
.mid {
  display: flex;
  width: 100%;
}
.body {
  margin: 50px;
  display: flex;
  width: 100%;
}
</style>

