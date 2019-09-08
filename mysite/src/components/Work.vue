<template>
  <div class="container">
    <div class="row title">
      <h2>Work</h2>
    </div>
    <div class="row pro-contain">
      <div class="col-md-3 project">
        <a href class="img-contain">
          <div class="desc">
            <h3>Project Name</h3>
            <span>Illustration</span>
          </div>
        </a>
      </div>
      <div class="col-md-3 project">
        <a href class="img-contain">
          <div class="desc">
            <h3>Project Name</h3>
            <span>Illustration</span>
          </div>
        </a>
      </div>
      <div class="col-md-3 project">
        <a href class="img-contain">
          <div class="desc">
            <h3>Project Name</h3>
            <span>Illustration</span>
          </div>
        </a>
      </div>
      <div class="col-md-3 project">
        <a href class="img-contain">
          <div class="desc">
            <h3>Project Name</h3>
            <span>Illustration</span>
          </div>
        </a>
      </div>
    </div>
    <div class="row pro-contain">
      <div class="col-md-3 project">
        <a href class="img-contain">
          <div class="desc">
            <h3>Project Name</h3>
            <span>Illustration</span>
          </div>
        </a>
      </div>
      <div class="col-md-3 project">
        <a href class="img-contain">
          <div class="desc">
            <h3>Project Name</h3>
            <span>Illustration</span>
          </div>
        </a>
      </div>
      <div class="col-md-3 project">
        <a href class="img-contain">
          <div class="desc">
            <h3>Project Name</h3>
            <span>Illustration</span>
          </div>
        </a>
      </div>
      <div class="col-md-3 project">
        <a href class="img-contain">
          <div class="desc">
            <h3>Project Name</h3>
            <span>Illustration</span>
          </div>
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.container {
  padding: 80px 0px;
}
.title {
  width: 100%;
  height: 140px;
}
.title h2 {
  width: 100%;
  text-align: center;
  color: #fff;
  letter-spacing: 1px;
  margin: 0px;
  font-size: 40px;
  font-weight: 400;
}

.project {
  padding: 6px;
  text-align: center;
}
.project .img-contain {
  display: inline-block;
  background-image: url(../assets/portfolio-6.jpg);
  background-size: cover;
  background-position: cneter center;
  background-repeat: no-repeat;
  height: 300px;
  width: 100%;
  transition: all 0.5s ease 0s;
  text-decoration: none;
}
.project .img-contain:hover {
  background-color: transparent;
}

.project .desc {
  height: 290px;
  width: 100%;
  background-color: #fff;
  opacity: 0;
  transition: all 0.5s ease 0s;
}
.project .img-contain:hover .desc {
  opacity: 1;
  height: 292px;
  width: 101%;
}

.project .img-contain h3 {
  padding-top: 95px;
  font-size: 22px;
  color: #000;
  transition: transform 0.3s, opacity 0.3s;
  transform: translate3d(0, -15px, 0);
}
.project .img-contain:hover h3 {
  transition: transform 0.3s, opacity 0.3s;
  transform: translate3d(0, 15px, 0);
  font-size: 22px;
  color: #000;
  padding-top: 95x;
}
.project .img-contain span {
  padding-top: 45px;
  display: block;
  color: #999;
  font-size: 16px;
  transition: transform 0.3s, opacity 0.3s;
  transform: translate3d(0, 15px, 0);
}
.project .img-contain:hover span {
  transition: transform 0.3s, opacity 0.3s;
  transform: translate3d(0, -15px, 0);
  /* display: block;   注意行级元素的动画问题 */
  display: block;
  color: #999;
  font-size: 16px;
  padding-top: 45px;
}
</style>