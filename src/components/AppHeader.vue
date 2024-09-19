<script>
export default {
  data() {
    return { 
      
    }
  }
}
</script>

<template>
<header>
  <div class="container d-flex justify-content-between py-3">
    <div>
      <img src="/img/construction_logo.png" alt="Logo">
    </div>
    <div>
      <ul class="d-flex list-unstyled py-5">
        <li>
          <a class="px-4" href="">HOME</a>
        </li>
        <li>
          <a class="px-4" href="">ABOUT</a>
        </li>
        <li>
          <a class="px-4" href="">SERVICES</a>
        </li>
        <li>
          <a class="px-4" href="">WORK</a>
        </li>
        <li>
          <a class="px-4" href="">ARTICLES</a>
        </li>
        <li class="square">
          <a id="A" class="px-4" href="">GET QUOTE</a>
        </li>
      </ul>
    </div>
  </div>
  <div class="BG">
    <div>
      <h1 class="h1 py-5">BUILDING INSPIRING SPACES</h1>
      <h2 class="h2">We Build Inspiring Residential & Commercial Spaces</h2>
      <div class="text-center py-5">
        <button class="B1">
          EXPLORE RECENT WORK
        </button>
        <button class="B2">
          GET A QUOTE TODAY
        </button>
      </div>
      
    </div>

  </div>
</header>

</template>

<style lang="scss">
// Import all of Bootstrap's CSS
@import "bootstrap/scss/bootstrap";

header{
  list-style: none;
}
a{
  text-decoration: none;
  color: black;
}
a:hover{
  color: orange;
}
.square{
  height: 25px;
  background-color: #fed03d;
}
#A{
  color: black;
}
.BG {
  padding-top: 120px;
  background-image:  url('../img/home-slider.jpg');
  min-height: 600px;
  
}
.h1{
  color: white;
  text-align: center;
  font-size: 4rem;
}
.h2{
  color: #fed03d;
  text-align: center;

}
.B1{
  background-color: #333333;
  color: white;
  height: 50px;
  margin-right: 10px;
  border: 1px solid black;
}
.B2{
  background-color: #fed03d;
  color: black;
  height: 50px;
  margin-left: 10px;
  border: 1px solid black;
}
</style>
