<script setup>

</script>

<template>
<div id="outer">
  <div id="content">
    <div style="display: flex;flex-direction: row;justify-content: space-evenly;align-items: center">
      <img style="width: 150px;" src="./assets/img/概念图.png" alt="">
      <div class="ref-card">
        <p style="text-align: center">
          "曾经我来过这里","风车见过我"
          <br/>
          "未来我要远去","黎明带走了我"
          <br/>
          "再见了故乡","再见了故乡"
        </p>
        <p style="font-size: 20px;text-align: right">--墟语者</p>
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
  </div>
</div>
</template>

<style scoped>
.float-left{
  float: left;
  clear: left;
}
.ref-card{
  display: inline-block;
  font-size: 18px;
  line-height: 1.8;
  background: rgba(24, 24, 24, 0.28);
  width: 400px;
  border-left: 10px solid black;
  color: #c9c0bd;
  padding: 10px 10px 6px;
}
#outer {
  background-image: url(./assets/img/冬日.png);
  background-size: cover;
  background-repeat: no-repeat;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100vh;
}
#content{
  background: rgba(98, 98, 98, 0.63);
  margin: 20px auto;
  width: 1000px;
  padding: 30px;
}
</style>
