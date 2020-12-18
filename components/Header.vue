<template>
  <div class="header">
    <ul class="list">
      <nuxt-link  to="/"><li>Home</li></nuxt-link>
      <nuxt-link  to="/"><li>Blog</li></nuxt-link>
      <nuxt-link  to="/"><li>Profile</li></nuxt-link>
      <nuxt-link  to="/"><li class="login"><small>Login</small></li></nuxt-link>
      <nuxt-link  to="/"><li class="login"><small>Sign Up</small></li></nuxt-link>
    </ul>

  </div>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style>

.list{
   display: flex;
  width: 100%;
  justify-content: flex-end;
}
.list li{
  display: inline-block;
  text-decoration: none;
  list-style-type: none;
  color: black;
  font-weight: 500;
  padding:10px 11px 10px 20px;
}
ul{
  position: fixed;
}
.login{
  background-color: black;
  color: white;
  margin:0px 10px 0px 0px;
}

small{
  color: white;
  padding:0px 10px 0px 0px;
}
</style>
