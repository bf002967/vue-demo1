<template>
  <div id="app">
    <m-header></m-header>
    <content-one></content-one>
    <content-two></content-two>
    <content-three></content-three>
    <m-footer></m-footer>

  </div>
</template>

<script>
import mHeader from './Header'
import ContentOne from "./ContentOne"
import ContentTwo from "./ContentTwo"
import ContentThree from "./ContentThree"
import mFooter from "./Footer"
export default {
  name: "App",
  components: {
    mHeader,
    ContentOne,
    ContentTwo,
    ContentThree,
    mFooter
  },
  data() {
    return {
      msg: "Welcome to Your Vue.js App"
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
*{
  margin: 0;
  padding: 0;
}
#app{
  margin: 0;
  padding: 0;
}
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
