<template>
  <div class="container">
    <div class="text-fields">
      <input type="text" class="title" placeholder="Title">
      <textarea type="text" class="article" placeholder="Write Here.."></textarea>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.container {
  margin: 5%;
  min-height: 100vh;
  /* text-align: center; */
}
.text-fields{
  margin:5%;
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
  font-size: 70px;
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
  font-size: 40px;
  width: 100%;
  color: #35495e;
  letter-spacing: 1px;
  min-height: 100vh;
}
/* button{
  position: relative;
  float: right;
  background-color:green;
  color:white;
  border: none;
  padding: 5px 12px;
  font-size: 15px;
  border-radius: 9%;
} */

</style>
