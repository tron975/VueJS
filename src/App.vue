<template>
  <HelloWorld message="Counter Game" />
</template>

<script setup>

 import HelloWorld from './components/HelloWorld.vue'
 


// This starter template is using Vue 3 experimental <script setup> SFCs
// Check out https://github.com/vuejs/rfcs/blob/script-setup-2/active-rfcs/0000-script-setup.md
</script>

<style>
body {
background-image: linear-gradient(to right, #52ff52,  #46bff6)
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  background-color: aqua;
  box-shadow: 0 0 20px blue;
  width: 700px;
  height: 150px;
  position: absolute;
  right: 33%;

}

#buttonState {
  border-radius: 8px;
  background-color: #7BB9FA;
  transition: 0.3s;
  text-emphasis: bold;
  color: white;
  box-shadow: 0 0 20px rgb(255, 255, 255);
  border: none;
  width: 150px;
  height: 35px;
  font-weight: bold;
  color: red;
  font-size: 18px;

 
}

#buttonState:hover {
  transform: scale(1.05);
  border: 1px solid red;
}

#increaseState {
  background-color: #7BB9FA;
  background-size: 200% auto;
  transition: 0.5s;
  border-radius: 8px;
  border: none;
  color: white;
  font-weight: bold;
  margin: 5px;
  width: 180px;
  height: 35px;
  text-align: center;  
  font-size: 15px;
}

#increaseState:hover {
  transform: translateY(-3px);
  cursor: pointer;
  background-position: right center;
  color: rgb(90, 89, 89);
}

#decreaseState {
  background-color: #7BB9FA;
  background-size: 200% auto;
  transition: 0.5s;
  border-radius: 8px;
  border: none;
  color: white;
  font-weight: bold;
  margin: 5px;
  height: 30px; 
  font-size: 15px;
}

#decreaseState:hover {
  transform: translateY(3px);
  cursor: pointer;
  background-position: right center;
  color: rgb(90, 89, 89);
}

#resetButton {
  background-color: #FE4E4E;
  color: white;
  border: none;
  cursor: pointer;
  border-radius: 8px;
  transition: 0.8s;
  height: 35px;
  width: 150px;
  font-size: 18px;
  font-family: sans-serif;

}

#resetButton:hover {
  box-shadow: 0 0 20px white;
  transform: translateX(8px);
  background-color: #f67f7f;
}
</style>
