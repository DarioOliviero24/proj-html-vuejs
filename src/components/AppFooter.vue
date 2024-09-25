<script>
export default {
  data() {
    return { 
      
    }
  }
}
</script>

<template>
    <!--BUILDING INSPIRING SPACES-->
    <div class="building-bg">
      <div class="d-flex container py-5 justify-content-between">
        <div class="py-5">
          <h4 class="h">Buildings Inspiring Spaces</h4>
          <hr class="hr3">
          <p class="p">
              Vivamus sed consecteur tellus dolor sit amet, consectetur adipiscing <br>
              lorem elit sadip ipsum ficilis uns.
          </p>
        </div>
      <div>
      <div class="py-5 text-center">
        <button type="button" class="btn btn-warning">GET A FREE QUOTE</button> 
        <p class="p py-3">
          Only takes a few seconds!
        </p>         
      </div>
    </div>
    </div>
    </div>
    <div class="BG-top">
      <div class="my-row container py-5 d-flex">
        <!--CARD-FOT1-->
        <div class="card-fot">
          <img src="/img/footer-logo.png" alt="logo">
          <p class="p py-4">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Alias nisi vero ipsum quo sunt excepturi ea eos recusandae non obcaecati!
          </p>
          <button type="button" class="btn btn-warning">LEARN MORE</button>
        </div>
        <!--CARD-FOT2-->
        <div class="card-fot">
          <h6 class="HF">LATEST TWEETS</h6>
          <div>
            <img src="/img/3a74ce3d0532b7773b174c45ca3bd05a_normal.png" alt="boh">
            <img src="/img/theme-fusion.png" alt="">
          </div>
          <div class="py-4">
            <img class="img-fot" src="/img/fusion2.png" alt="fusion2">
          </div>
          
        </div>
        <!--CARD-FOT3-->
        <div class="card-fot">
          <h6 class="HF">CONTACT US TODAY</h6>
          <div class="py-2">
            <img src="/img/contact-us.png" alt="contact">
          </div>
          
        </div>
        <!--CARD-FOT4-->
        <div class="card-fot">
          <h6 class="HF">FIND US</h6>
          <div>
            <img src="/img/findus.png" alt="find us">
          </div>
          
        </div>
        

      </div>

    </div>

</template>

<style lang="scss">
// Import all of Bootstrap's CSS
@import "bootstrap/scss/bootstrap";

.building-bg{
    background-image: url('img/about-call-to-action-57862405.jpg');
    height: 400px;
}

.hr3{
    width: 150px;
    margin-top: 30px;
    margin-bottom: 30px;
    color: #fed03d;
    border: 3px solid #fed03d;
}
.p{
    color: white;
}
.h{
  color: white;
}
//footer top
.BG-top{
  background-color: #1e1e1e;
  height: 500px;

}
.card-fot{
  height: 450px;
  width: 310px;
  margin: 0 auto;
}
.HF{
  color: #fed03d;
}
.img-fot{
  width: 100%;
}
</style>
