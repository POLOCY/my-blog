<template>
    <nav>
      <ul>
        <li>
          <router-link to="/" exact="">博客</router-link>
          <router-link to="/add" exact="">写博客</router-link>
        </li>
      </ul>
    </nav>
</template>

<script>
    export default {
        name: "blog-header"
    }
</script>

<style scoped>
  ul{
    list-style-type: none;
    text-align: center;
    margin: o;
  }
  li{
    display: inline-block;
    margin: 0 10px;
  }
  a{
    color: #fff;
    text-decoration: none;
    padding: 12px;
    border-radius: 5px;
  }
  nav{
    background: crimson;
    padding: 30px 0;
    margin-bottom: 40px;
  }
.router-link-active{
    background: rgba(225,225,255,0.5);
    color: #444;
  }
</style>
