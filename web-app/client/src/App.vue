<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/siheung.png">    
      <br>
        <router-link to="/">홈</router-link>&nbsp;          
        <router-link to="/getCurrentStanding">투표 현황</router-link>&nbsp;
        <router-link to="">나가기</router-link>&nbsp;
      
      <router-view></router-view>
    </div>
</template>

<script>

export default {
  name: 'app'  
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.chart-wrapper {
  width: 100%;
  height: 700px;
}
.echarts {
  width: 100%;
  height: 100%;
}

#loader {
  position:fixed;
  padding-top: 250px;
}

.chart-wrapper {
  position:fixed;
  padding-left:32%;
}
</style>
