<template>
  <div class="home">
    
    <div class="img-container">
      <img src="../assets/cover_bg_3.jpg" alt />
    </div>
    <!-- <div class="overlay"></div> -->
    <!-- 头部容器 -->
    <Header></Header>
    <!-- 个人信息 -->
    <Content class="content"></Content>
    <div class="line"></div>
    <!-- 技能描述 -->
    <Skill></Skill>
  </div>
</template>

<script>
import Header from "../components/Header.vue"
import Content from "../components/Content.vue"
import Skill from "../components/Skill.vue"
export default {
  name: "home",
  components: {
    Header,
    Content,
    Skill,
  }
};
</script>
<style scoped>
.home{
  background-color: rgba(0, 173, 181, 0.9);
}
.line{
  width: 100%;
  border-bottom: 1px dotted #333;
}
.img-container {
  height: 720px;
  width: 100%;
  position: absolute;
  z-index: -2;
}
.img-container img {
  width: 100%;
  height: 100%;
  background-color: transparent;
}
/* .overlay {
  height: 720px;
  width: 100%;
  position: absolute;
  z-index: -1;
  background-color: #00ADB5;
} */
.content{
  margin-top: 60px;
}
</style>
