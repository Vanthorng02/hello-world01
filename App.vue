<template>
  <div id="app">
    <div>
      <h3>ចន្ទត្រា កុំព្យូទ័រ</h3>
      <img class="object-none object-left-top w-24 h-24" alt="Vue logo" src="./assets/logo.png" >

    </div>
    <!-- call frorm another vue -->
    <HelloWorld msg="Hello Vue in CodeSandbox!"/>
    <button class="bg-indigo-500 ...">
  Save changes
</button>
  </div>
</template>
<script src="https://cdn.tailwindcss.com"></script>
<script>
import HelloWorld from "./components/HelloWorld";

export default {
  name: "App",
  components: {
    HelloWorld
  }
};
</script>


<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
@import url('https://fonts.googleapis.com/css2?family=Moul&display=swap');
.font-family: 'Moul', cursive;
</style>
