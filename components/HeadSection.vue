<template>
  <div class="app">
    <div class="text">
      <h1 class="head">Hi, I am John, Creative Technologist</h1>
      <br>
      <p class="desc">
        Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet sint.
        Velit officia consequat duis enim velit mollit.
        Exercitation veniam consequat sunt nostrud amet.
      </p>
      <br>
        <button class="button">Download Resume</button>
    </div>
  <div class="image">
      <img src="../assets/book2.png" width="170%"/>
  </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
*{
  margin: 0;
  box-sizing: border-box;

}
.app{
  display: flex;
  justify-content: center;
  align-items: center;
}
.text{
  color: #21243D;
  padding: 80px 100px 0px 60px;
  flex: 2;
  min-height: 70vh;
}
.head{
  font-size: 40px;
  text-align: left;
}
.desc{
  text-align: left;

}
.button{
  padding: 10px;
  background-color: #FF6464;
  color: white;
  margin-left: 0%;
  border: none;

}
.image{
  flex:1;
}
</style>
