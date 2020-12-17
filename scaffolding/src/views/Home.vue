<template>
  <div>
    <div class="bj">
      <img src="../assets/images/1.png" alt="" />
    </div>
    <div class="head">
      <a href="">首页</a>
      <a href="" class="a1">关于真声</a>
      <a href="" class="a2">商务合作</a>
    </div>
    <!-- <div class="tetle1">炫酷特效</div>
    <div class="tetle2">支持私聊</div>
    <div class="tetle3">桌游游戏</div> -->
    <div class="button">
      <button class="button1">
        <img src="../assets/images/2.png" alt="" />
        <span>Android</span>
      </button>
      <button class="button2">
        <img src="../assets/images/3.png" alt="" />
        <span>AppStore</span>
      </button>
    </div>
  </div>
</template>

<style>
* {
  margin: 0;
  padding: 0;
}
.bj > img {
  width: 100%;
  height: 100%;
}
.a1 {
  left: 840px;
}
.a2 {
  left: 1140px;
}
a {
  height: 10px;
  color: red;
  font-size: 40px;
  font-family: PingFang SC;
  padding: 100px;
  box-sizing: border-box;
  text-decoration: none;
  position: absolute;
  left: 620px;
  top: -54px;
  align-items: center;
  display: block;
  /* padding: 0; */
}

.head > a:hover {
  /* border-bottom: 12px solid #f00;
  color: #f00;
  border-radius: 4px; */
}
.button2 {
  top: 690px;
}
button {
  width: 300px;
  height: 90px;
  background: #ffffff;
  border-radius: 45px;
  border: 0;
  outline: none;
  position: absolute;
  left: 1100px;
  top: 580px;
}
button > img {
  width: 42px;
  height: 50px;
}
button > span {
  width: 176px;
  height: 38px;
  font-size: 40px;
  font-family: PingFang SC;
  font-weight: bold;
  color: #333333;
  line-height: 30px;
}
/* .tetle1,
.tetle2,
.tetle3 {
  font-size: 79px;
  font-family: PingFang SC;
  font-weight: 800;
  color: #666666;
  line-height: 73px;
  background: linear-gradient(0deg, #f487fc 0%, #ed39fa 100%);
} */
</style>
