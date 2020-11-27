<template>
  <div class="mid">

      <h4 class="recent">Recent posts</h4>
      <nuxt-link to="/"><li>View all</li></nuxt-link>

    <div class="card">
      <div class="card1">
        <h2>Making a design system from scratch</h2>
        <br>
        <p>12 Feb 2020 | Design Pattern</p>
        <br>
        <p>Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet sint.
           Velit officia consequat duis enim velit mollit.
           Exercitation veniam consequat sunt nostrud amet.
        </p>
      </div>
      <div class="card1">
        <h2>Making a design system from scratch</h2>
        <br>
        <p>12 Feb 2020 | Design Pattern</p>
        <br>
        <p>Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet sint.
           Velit officia consequat duis enim velit mollit.
           Exercitation veniam consequat sunt nostrud amet.
        </p>
      </div>

    </div>



  </div>
</template>

<script>
export default {

}
</script>

<style>
 .mid{
   background-color: #EDF7FA;
   min-height: 50vh;

 }
.card{
  display: flex;
}
.card1{
  background-color: white;
  color: #21243D;
  flex: 1;
  margin: 60px 0px 10px 70px;
  padding: 30px;
}
li{
  float: right;
  list-style-type: none;
}
.recent{
  padding: 25px 0px 0px 35px;
}
</style>
