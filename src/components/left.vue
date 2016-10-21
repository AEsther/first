<template>
  <div class="left">
      nav
      <ul>
        <li v-for="v in nav">{{v}}</li>
      </ul>
  </div>
</template>

<script>
export default {
  name: 'top',
  data () {
    return {
        nav:["nav1","nav2","nav3"]
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
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
.top{
  width:100%;
  height:50px;
  line-height:50px;
  background:red;
}
.left{
  width:20%;
  height:500px;
  float:left;
  background:green;
}
</style>
