<template>
  <div class="container">
    <!-- 圆形百分比问题 -->
    <div class="row">
      <div class="col-md-12 title">
        <h2>Skills</h2>
      </div>
    </div>
    <div class="row">
      <div class="col-md-3 col-sm-6 col-xs-12 text-center">
        <div class="chart">
          <span>
            <strong style="display: block;">HTML5</strong>95%
          </span>
          <canvas class="canvas" ref="canvas" height="160" width="160" data-percent="95"></canvas>
        </div>
      </div>
      <div class="col-md-3 col-sm-6 col-xs-12 text-center">
        <div class="chart">
          <span>
            <strong style="display: block;">CSS3</strong>98%
          </span>
          <canvas class="canvas" ref="canvas" height="160" width="160" data-percent="98"></canvas>
        </div>
      </div>
      <div class="col-md-3 col-sm-6 col-xs-12 text-center">
        <div class="chart">
          <span>
            <strong style="display: block;">VUE</strong>89%
          </span>
          <canvas class="canvas" ref="canvas" height="160" width="160" data-percent="89"></canvas>
        </div>
      </div>
      <div class="col-md-3 col-sm-6 col-xs-12 text-center">
        <div class="chart">
          <span>
            <strong style="display: block;">NODE</strong>93%
          </span>
          <canvas class="canvas" ref="canvas" height="160" width="160" data-percent="93"></canvas>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col-md-3 col-sm-6 col-xs-12 text-center">
        <div class="chart">
          <span>
            <strong style="display: block;">HTML5</strong>95%
          </span>
          <canvas class="canvas" ref="canvas" height="160" width="160" data-percent="95"></canvas>
        </div>
      </div>
      <div class="col-md-3 col-sm-6 col-xs-12 text-center">
        <div class="chart">
          <span>
            <strong style="display: block;">CSS3</strong>98%
          </span>
          <canvas class="canvas" ref="canvas" height="160" width="160" data-percent="98"></canvas>
        </div>
      </div>
      <div class="col-md-3 col-sm-6 col-xs-12 text-center">
        <div class="chart">
          <span>
            <strong style="display: block;">VUE</strong>89%
          </span>
          <canvas class="canvas" ref="canvas" height="160" width="160" data-percent="89"></canvas>
        </div>
      </div>
      <div class="col-md-3 col-sm-6 col-xs-12 text-center">
        <div class="chart">
          <span>
            <strong style="display: block;">NODE</strong>93%
          </span>
          <canvas class="canvas" ref="canvas" height="160" width="160" data-percent="93"></canvas>
        </div>
      </div>
    </div>

    <!-- 进度条部分 -->
    <div class="row">
      <div class="col-md-6 pro-container">
        <h3 class="category">
          <span>HTML5</span>
          <span>95%</span>
        </h3>
        <div class="progress">
          <div
            class="progress-bar progress-bar-1 progress-bar-striped active"
            role="progressbar"
            aria-valuenow="95"
            aria-valuemin="0"
            aria-valuemax="100"
            style="width: 95%"
          >
            <span class="sr-only">45% Complete</span>
          </div>
        </div>
      </div>
      <div class="col-md-6 pro-container">
        <h3 class="category">
          <span>CSS3</span>
          <span>98%</span>
        </h3>
        <div class="progress">
          <div
            class="progress-bar progress-bar-2 progress-bar-striped active"
            role="progressbar"
            aria-valuenow="98"
            aria-valuemin="0"
            aria-valuemax="100"
            style="width: 98%"
          >
            <span class="sr-only">45% Complete</span>
          </div>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col-md-6 pro-container">
        <h3 class="category">
          <span>VUE</span>
          <span>89%</span>
        </h3>
        <div class="progress">
          <div
            class="progress-bar progress-bar-3 progress-bar-striped active"
            role="progressbar"
            aria-valuenow="89"
            aria-valuemin="0"
            aria-valuemax="100"
            style="width: 89%"
          >
            <span class="sr-only">45% Complete</span>
          </div>
        </div>
      </div>
      <div class="col-md-6 pro-container">
        <h3 class="category">
          <span>NODE</span>
          <span>93%</span>
        </h3>
        <div class="progress">
          <div
            class="progress-bar progress-bar-4 progress-bar-striped active"
            role="progressbar"
            aria-valuenow="93"
            aria-valuemin="0"
            aria-valuemax="100"
            style="width: 93%"
          >
            <span class="sr-only">45% Complete</span>
          </div>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col-md-6 pro-container">
        <h3 class="category">
          <span>HTML5</span>
          <span>95%</span>
        </h3>
        <div class="progress">
          <div
            class="progress-bar progress-bar-5 progress-bar-striped active"
            role="progressbar"
            aria-valuenow="95"
            aria-valuemin="0"
            aria-valuemax="100"
            style="width: 95%"
          >
            <span class="sr-only">45% Complete</span>
          </div>
        </div>
      </div>
      <div class="col-md-6 pro-container">
        <h3 class="category">
          <span>CSS3</span>
          <span>98%</span>
        </h3>
        <div class="progress">
          <div
            class="progress-bar progress-bar-6 progress-bar-striped active"
            role="progressbar"
            aria-valuenow="98"
            aria-valuemin="0"
            aria-valuemax="100"
            style="width: 98%"
          >
            <span class="sr-only">45% Complete</span>
          </div>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col-md-6 pro-container">
        <h3 class="category">
          <span>VUE</span>
          <span>89%</span>
        </h3>
        <div class="progress">
          <div
            class="progress-bar progress-bar-7 progress-bar-striped active"
            role="progressbar"
            aria-valuenow="89"
            aria-valuemin="0"
            aria-valuemax="100"
            style="width: 89%"
          >
            <span class="sr-only">45% Complete</span>
          </div>
        </div>
      </div>
      <div class="col-md-6 pro-container">
        <h3 class="category">
          <span>NODE</span>
          <span>93%</span>
        </h3>
        <div class="progress">
          <div
            class="progress-bar progress-bar-8 progress-bar-striped active"
            role="progressbar"
            aria-valuenow="93"
            aria-valuemin="0"
            aria-valuemax="100"
            style="width: 93%"
          >
            <span class="sr-only">93% Complete</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import $ from "jquery";
export default {
  data() {
    return {};
  },
  mounted() {
    // 取到所有的画布元素
    let canvas = $(".canvas");
    // 生成一个画布元素的数组
    let canvasArr = [...canvas];

    // 循环每一个画布元素
    canvasArr.forEach((item, index) => {
      // 取到对应的技能百分数
      let rate = parseInt(item.attributes[3].nodeValue) / 100;
      // 定义起始角度
      let startDegree = 1.5 * Math.PI;
      // 定义结束角度
      let endDegree = 0;

      // 根据相关条件算出结束角度
      if (rate < 0.25) {
        endDegree = startDegree + endDegree;
      } else {
        endDegree = 2 * rate * Math.PI - 2 * 0.25 * Math.PI;
      }

      // 根据生成的参数进行画出相关的图形
      let context = item.getContext("2d");
      context.beginPath();
      context.arc(80, 80, 77, startDegree, endDegree);
      context.lineWidth = 3;
      context.stroke();
    });
  }
};
</script>

<style scoped>
.container {
  padding: 112px 0px;
}
.title {
  margin-bottom: 56px;
}
.title h2 {
  text-align: center;
  font-size: 40px;
  margin-bottom: 20px;
  line-height: 1.5;
  color: #000;
  letter-spacing: 3px;
}

.chart {
  width: 160px;
  height: 160px;
  margin-bottom: 30px;
  font-weight: 400;
  font-size: 17px;
  line-height: 1.7;
  color: #4d4d4d;
  position: relative;
}

.chart canvas {
  position: absolute;
  left: 0;
  top: 0;
}
.chart strong {
  font-weight: bolder;
  letter-spacing: 1.1px;
}
.chart span {
  position: relative;
  top: 43px;
  left: 3px;
}
.pro-container {
  margin: 50px 0px;
}
.progress-bar,
.progress {
  height: 5px;
}
.progress.active .progress-bar,
.progress-bar.active {
  animation: progress-bar-stripes 2s linear infinite;
}
.progress-bar.progress-bar-1 {
  background-color: #2980b9 !important;
}
.progress-bar.progress-bar-2 {
  background-color: #c0392b !important;
}
.progress-bar.progress-bar-3 {
  background-color: #d35400 !important;
}
.progress-bar.progress-bar-4 {
  background-color: #8e44ad !important;
}
.progress-bar.progress-bar-5 {
  background-color: #27ae60 !important;
}
.progress-bar.progress-bar-6 {
  background-color: #2F3C4F;
}
.progress-bar.progress-bar-7 {
  background-color: #2980b9 !important;
}
.progress-bar.progress-bar-8 {
  background-color: #d35400 !important;
}


.category {
  font-size: 16px;
  margin-bottom: 10px;
  width: 100%;
  display: flex;
  justify-content: space-between;
}
</style>