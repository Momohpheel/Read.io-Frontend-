<template>
  <div class="container">
    <div class="text-fields">
      <p>Register With Us</p>
      <input type="text" class="title" placeholder="E-mail">
      <input type="text" class="article" placeholder="Username">
      <input type="text" class="title" placeholder="Password">
      <input type="text" class="article" placeholder="Occupation">
      <input type="text" class="title" placeholder="Phone">
      <textarea type="text" class="description" placeholder="Description"></textarea>
      <div>
        <button>Login</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.container {
  margin-top: 5%;
  padding: 2% 10% 10% 10%;
  margin-left: 15%;
  width: 50%;
  box-shadow: 0px 24px 44px rgba(0, 0, 0, 0.1);
  /* text-align: center; */
}
.text-fields p:first-child{
  font-weight: 300;
  font-size: 30px;
  color: #35495e;
  letter-spacing: 1px;
  text-align: center;
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 30px;
  color: #35495e;
  letter-spacing: 1px;
  border: none;
  width: 100%;
}
.title:focus{
  outline: none;
}
.article:focus{
  outline: none;
}
.article {
  border: none;
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 30px;
  width: 100%;
  color: #35495e;
  letter-spacing: 1px;

}
.description {
  border: none;
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 30px;
  width: 100%;
  color: #35495e;
  letter-spacing: 1px;
  min-height: 20vh;
}
button{
  padding: 10px 20px;
  background-color: rgb(27, 27, 51);
  color: white;
  border: none;
  border-radius: 5%;
  box-shadow: 0px 24px 44px rgba(0, 0, 0, 0.1);
  position: relative;
  float: right;
}

</style>
