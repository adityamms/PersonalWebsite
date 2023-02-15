<template>
    <h1 style="color: white; position: relative; top: 1000px;text-align: center;" data-aos="fade-left" data-aos-duration="1200">what people said</h1>
    <div style="position: relative; top: 1200px;" id="testi">
        <div id="carouselExampleIndicators" class="carousel slide">
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
  </div>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <div class="wrap">
        <div class="kotak-isi" >
            <img src="../img/aku-suka-cara-pikirannya-berpikir.jpg" alt="orang">
            <div>
                <q>I love the design</q>
            </div>
        </div>
        <div class="kotak-isi">
            <img src="../img/dia-didedikasikan-untuk-desainnya.jpg" alt="orang">
            <div>
                <q>This is Amazing</q>
            </div>
        </div>
      </div>
    </div>
    <div class="carousel-item">
      <div class="wrap">
        <div class="kotak-isi">
            <img src="../img/istockphoto-612744166-612x612.jpg" alt="orang">
            <div>
                <q>love the animation</q>
            </div>
        </div>
        <div class="kotak-isi">
            <img src="../img/pemuda-jenggot-ceria-tersenyum-ke-arah-kamera.jpg" alt="orang">
            <div> 
                <q>very responsive</q>
            </div>
        </div>
      </div>
    </div>
    <div class="carousel-item">
      <div class="wrap">
        <div class="kotak-isi">
            <img src="../img/potret-pengusaha-terkejut.jpg" alt="orang">
            <div>
                <q>the web support phone view</q>
            </div>
        </div>
        <div class="kotak-isi">
            <img src="../img/pria-berdiri-di-dapur.jpg" alt="orang">
            <div>
                <q>very cheap price</q>
            </div>
        </div>
      </div>
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>       
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
#testi{
    .kotak-isi{
        width: 500px;height: 200px; 
        border:2px solid white;
        border-radius: 20px;
        background-color: rgb(22, 22, 22);
        overflow: hidden;
    }
    .wrap{
        width: 100%;
        display: flex;
        justify-content: space-evenly;
    }
    img{
        position: relative;
        aspect-ratio: 1;
        width: 100px;
        top: 10px;
        left: 10px;
        height: 50px;width: 50px; border-radius: 50%;
        border: 1px solid white;
        object-fit:cover;
    }
    q{
        color:white;
        position: relative;
        top: 10px;
        font-size: 30px;
        display: flex;
        align-items: center;
        justify-content: center;
    }
    @media only screen and (max-width: 1026px)  {
        .wrap{
            display: grid;
            gap: 0px;
        }
        .kotak-isi{
            transform: scale(.6);
        }
    }
  
 
}
</style>