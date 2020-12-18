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
  padding:0;
}
.app{
  width:80%;
  display: flex;
  justify-content: center;
  align-items: center;
}
.text{
  width:50%;
  display: flex;
  flex-direction: column;
  justify-content: center;

  color: #21243D;
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
width: 30%;
}
.image{

  width:30%;

}
</style>
