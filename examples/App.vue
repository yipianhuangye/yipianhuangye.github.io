<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <Demo></Demo>
    <m-card></m-card>
    <m-card
    imgSrc="1.png"
    summary="玩转组件库搭建全流程"
    ></m-card>
<br/>
     <m-card
    imgSrc="2.png"
    summary="基于Element-UI二次封装业务组件"
    >
    <template v-slot:footer>
      <div class="footer"> 
        <div class="level">进阶 · 10632人报名</div>
        <div class="proce">免费</div>
      </div>
    </template>
    </m-card>
    <br/>
    <m-card
    imgSrc="3.png"
    :width="370"
    :imgHeight="90"
    >
    Phaser从0到1实战微信2D小游戏【钢琴方块】Phaser从0到1实战微信2D小游戏【钢琴方块】
    <template v-slot:footer>
      <div class="footer-spring">
        <div class="level">进阶 · 3684人报名</div>
        <div class="proce">6人收藏</div>
      </div>
    </template>
    </m-card>
    <br/>
  </div>
</template>

<script>

export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.footer{
  padding: 0 8px;
  font-size: 12px;
  text-align: left;
}

.level{
  color: #9199A1;
  margin-bottom: 8px;
}
.price{
  color: #F01414;
}
.footer-spring{
  display: flex;
  justify-content: space-between;
  padding: 0 8px;
  font-size: 12px;
}
</style>
