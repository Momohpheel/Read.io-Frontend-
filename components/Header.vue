<template>
  <div class="header">
    <ul class="list">
      <nuxt-link  to="/"><li>Home</li></nuxt-link>
      <nuxt-link  to="/"><li>Blog</li></nuxt-link>
      <nuxt-link  to="/"><li>Profile</li></nuxt-link>
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
  float: right;
  margin-right: 50px;
  margin-top: 10px;
}
.list li{
  display: inline-block;
  padding: 10px;
  text-decoration: none;
  list-style-type: none;
  color: black;
  font-weight: 500;

}

</style>
