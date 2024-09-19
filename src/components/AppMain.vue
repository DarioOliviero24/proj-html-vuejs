<script>
export default {
  data() {
    return { 
      
    }
  }
}
</script>

<template>
  <main>
    <div class="BG2">
        <h3 class="py-5 text-center">
            Do You Have A Construction Project We Can Help With?
        </h3>
        <div class="text-center">
        <button class="B3">
            GET A FREE QUOTE
        </button>
        </div>
        <div class="container">
            <div class="py-5 text-center">
                <h4>
                    Specialists In Modern Construction
                </h4>
                <hr class="hr">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Pariatur vero exercitationem quibusdam quis suscipit,<br>
                   sint velit alias magnam, impedit, iste expedita! Natus, animi esse temporibus voluptatum aut debitis?</p>
                
            </div>
            <div class="container d-flex">
                <div class="card">

                </div>
                <div class="card">

                </div>
                <div class="card">

                </div>
                <div class="card">

                </div>
                
            </div>
        </div>

    </div>
  </main>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

.BG2{
    background-color: #fed03d;
    height: 160px;    
}
.B3{
    background-color: black;
    color: white;
    height: 40px;
    border: 1px solid white;
}
.hr{
    width: 10%;
    margin-left: 780px;
    margin-top: 30px;
    color: #fed03d;
}
.card{
    height: 300px;
    width: 300px;
    margin-left: 25px;
    background-color: #f5f5f5;
    border: 1px solid #f5f5f5;
    margin-bottom: 100px;
}
</style>
