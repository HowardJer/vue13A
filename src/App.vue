<template> 
    <div>
      <h1>3 Vue Components</h1>
      <my-header></my-header>
      <my-body></my-body>
      <my-footer></my-footer>
    </div>
</template>

<script>
import Header from "./components/Header";
import Footer from "./components/Footer";
import Body from "./components/Body";

export default {
  components: {
    "my-header":Header,
    "my-footer":Footer,
    "my-body":Body
  }
 };
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;  
  body: {
    font-size: 2rem;
  }
}
</style>
