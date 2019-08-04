<template>
  <div id="app">
    <Header />
    <router-view />
  </div>
</template>

<script>
import Header from "./components/layout/Header";
export default {
  name: "app",
  components: {
    Header
  }
};
</script>


<style>
* {
  box-sizing: border-box;
  margin: 10px 10px;
  padding: 10px 10px;
}

body {
  font-family: Arial, Helvetica, sans-serif;
  line-height: 1.4;
}

.btn {
  display: inline-block;
  border: none;
  background: rgb(124, 117, 117);
  color: #fff;
  margin: 1px;
  padding: 7px 20px;
  cursor: pointer;
}

.btn:hover {
  background: rgb(151, 145, 145);
}
</style>
