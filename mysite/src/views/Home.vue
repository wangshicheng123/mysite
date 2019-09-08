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
    <div class="line"></div>
    <!-- 作品展示 -->
    <Work></Work>
    <div class="line"></div>
    <!-- 底部信息 -->
    <Footer></Footer>
  </div>
</template>

<script>
import Header from "../components/Header.vue"
import Content from "../components/Content.vue"
import Skill from "../components/Skill.vue"
import Work from "../components/Work.vue"
import Footer from "../components/Footer.vue"
export default {
  name: "home",
  components: {
    Header,
    Content,
    Skill,
    Work,
    Footer
  }
};
</script>
<style scoped>
.home{
  background-color: rgba(0, 173, 181, 0.9);
}
.line{
  width: 100%;
  border-bottom: 1px dotted #fff;
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
.content{
  margin-top: 60px;
}
</style>
