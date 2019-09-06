<template>
  <div class="home">
    <!-- 头部容器 -->
    <div class="img-container">
      <img src="../assets/cover_bg_3.jpg" alt />
    </div>
    <div class="overlay"></div>
    <div class="container">
      <div class="row">
        <div class="col-md-12">
          <div class="profile-container">
            <div class="img">
              <img src="../assets/user-3.jpg" alt />
            </div>
            <div class="name">
              <span class="left"></span>
              <span class="name-text">Louie Jie Mahusay</span>
              <span class="right"></span>
            </div>
            <div class="major">
              <h3>
                <span class="my-major">Web Developer / Photographer</span>
              </h3>
            </div>
            <div class="blog">
              <ul>
                <li>
                  <a href="#">
                    <img src="../assets/github.png" alt="">
                  </a>
                </li>
                <li>
                  <a href="#">
                    <img src="../assets/jianshu.png" alt="">
                  </a>
                </li>
                <li>
                  <a href="#">
                    <img src="../assets/csdn.png" alt="">
                  </a>
                </li>
                <li>
                  <a href="#">
                    <img src="../assets/mao.png" alt="">
                  </a>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "home",
  components: {
    // HelloWorld
  }
};
</script>
<style scoped>
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
.overlay {
  height: 720px;
  width: 100%;
  position: absolute;
  z-index: -1;
  background-color: #00ADB5;
}
.container {
  width: 750px;
  padding: 0px 15px;
  margin: auto;
  height: 657px;
  transform: translateY(20%);
}
.profile-container {
  /* height: 657px; */
}
.profile-container .img {
  width: 100%;
  text-align: center;
}
.profile-container img {
  width: 200px;
  height: 200px;
  border-radius: 50%;
}

.profile-container .name {
  margin: 30px 0px 20px 70px;
  transform: rotate(-5deg);
}
.name .left,
.name .right {
  display: inline-block;
  width: 34px;
  height: 4px;
  background: #fff;
  position: relative;
  top: -15px;
}
.name .name-text {
  color: #ffffff;
  font-size: 50px;
  line-height: 1.3;
  font-weight: 500;
  font-family: "Kaushan Script", cursive;
  padding: 4px 15px;
}
.profile-container .major {
  text-align: center;
  margin-top: 20px;
}
.major .my-major {
  font-size: 18px;
  color: #fff;
  font-family: "Space Mono", Arial, serif;
  font-weight: 400;
}

.profile-container .blog {
  margin: 25px 0px;
  transform: translateX(30%);
}
.blog ul {
  list-style: none;
  width: 300px;
  height: 30px;
  padding: 0px;
  margin: 0px;
}
.blog ul li {
  width: 30px;
  height: 30px;
  padding: 0px 10px;
  float: left;
  margin-left: 27px;
}
.blog ul li img{
  width: 30px;
  height: 30px;
  border-radius: 50%;
  background-color: #fff;
}
</style>
