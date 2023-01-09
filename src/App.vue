<script setup>

</script>

<template>
<div id="outer">
  <div id="content">
    <div style="display: flex;flex-direction: row;justify-content: space-evenly;align-items: center">
      <img style="width: 150px;" src="./assets/img/标志图.png" alt="">
      <div class="ref-card">
        <p style="text-align: center">
          "历史的选择绝不是为了人类的利益."
          <br/>
          "盲目的历史女神克丽欧，愿你能在未来作出正确的选择"
          <br/>
          "灾难是历史作出的选择"
        </p>
        <p style="font-size: 20px;text-align: right">--克里欧计划</p>
      </div>
    </div>
    <p style="color: var(--base-color);font-size: 17px;line-height: 2.0;text-align: center">
      "未知的旅途"
      <br>
      "迷途的异乡人"
      <br>
      "谁能知晓航标的方向"
    </p>
    <p style="font-size: 26px;text-align: center;color: var(--base-color)">向着未来旅行的故事...</p>
    <div class="float-left colum">
      <div style="width: 90%;margin: auto">
        <p style="margin:0;color:#d7d6d6;background: rgba(34,34,34,0.44);text-align: center;line-height: 2.0;font-size: 26px">最近更新</p>
        <div class="update-card">
          <img style="vertical-align: center;height: 100%;display: inline" src="./assets/img/最新更新.png" alt="">
          <p style="position:relative;top:-50%;display:inline-block;text-align: left;margin: 0 0 0 10px;font-size: 20px;color: antiquewhite">添加了人物介绍栏目</p>
        </div>
      </div>
    </div>
    <div class="float-right colum">
      <p style="font-size: 50px;color: #e1e1e1;text-align: center;margin: 0;">选择栏目</p>
      <p class="select-card">
        人 物 介 绍
      </p>
      <p class="select-card">
        故 事 章 节
      </p>
    </div>
    <div style="clear: both;"></div>
  </div>
</div>
</template>

<style scoped>
.select-card:hover{
  box-shadow: none;
  transition: 0.5s;
}
.select-card{
  font-size: 40px;
  color: #cedce5;
  font-style: italic;
  background: rgba(34, 34, 34, 0.24);
  text-align: center;
  margin: 10px auto;
  box-shadow:
      2.8px 2.8px 2.2px rgba(0, 0, 0, 0.02),
      6.7px 6.7px 5.3px rgba(0, 0, 0, 0.028),
      12.5px 12.5px 10px rgba(0, 0, 0, 0.035),
      22.3px 22.3px 17.9px rgba(0, 0, 0, 0.042),
      41.8px 41.8px 33.4px rgba(0, 0, 0, 0.05),
      100px 100px 80px rgba(0, 0, 0, 0.07);
  cursor: pointer;
  transition: 0.5s;
}
.update-card{
  height: 60px;
  display: flow-root;
  background: rgba(34, 34, 34, 0.09);
}
.colum{
  width: 50%;
}
.float-right {
  float: right;
  clear: right;
}
.float-left{
  float: left;
  clear: left;
}
.ref-card{
  display: inline-block;
  font-size: 18px;
  line-height: 1.8;
  background: rgba(24, 24, 24, 0.28);
  width: 600px;
  border-left: 10px solid black;
  color: #c9c0bd;
  padding: 10px 10px 6px;
}
#outer {
  background-image: url(./assets/img/冬日.png);
  background-size: cover;
  background-repeat: no-repeat;
  height: 100vh;
  display: flow-root;
}
#content{
  background: rgba(98, 98, 98, 0.63);
  margin: 20px auto;
  width: 1150px;
  padding: 30px;
}
</style>
