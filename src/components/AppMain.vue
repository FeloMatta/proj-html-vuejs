<script>
export default{
  name: 'AppMain',
  
}
</script>

<template>
  <main>
    <div id="first-section" class="d-flex justify-content-center align-items-center">
      <div class="container">
        <div>
          <!-- GET AVADA -->
          <div>
            <h1>
              Tech Forum!
            </h1>
            <p class="p-3">
              Discuss all the latest technology news and trends
            </p>
            <button class="btn my-btn rounded-1 py-3 px-5" type="button">
              GET AVADA NOW! >
            </button>
          </div>
          <!-- / GET AVADA -->
        </div>
      </div>
    </div>
    <!-- AVADA FORUM IS THE PLACE TO BE -->
    <div id="second-section" class="d-flex justify-content-center align-items-center">
      <div>
        <h3>AVADA FORUM IS THE PLACE TO BE</h3>
        <p>
          In quis lectus sed leo elementum  faucibus in dapibus dictum. <br>
          Nulla molestie tortor nec lectus venenatis, sed blandit dui finibus. <br>
          dolor at, bibendum purus. Donec vehicula nec tortor ac finibus.
        </p>
      </div>
    </div>
    <!-- / AVADA FORUM IS THE PLACE TO BE -->

    <!-- ALL THE LATEST NEWS -->
    <div id="third-section" class="">
      <div class="py-5">
        <P>PHASELLUS EGET METUS</P>
        <h1>
          All the <span class="my-underline">latest</span> news
        </h1>
      </div>
      <div class="container text-center py-5">
        <div class="row">
        <div class="col">
          <img src="../assets/img/post_feat_img_25-320x202.jpg" alt="">
          <h4>
            Morbi vitae dui euismod vulputate sollicitudin
          </h4>
          <p>
            October
          </p>
          <p class="py-2">
            Donec
          </p>
        </div>
        <div class="col">
          <img src="../assets/img/post_feat_img_24-320x202.jpg" alt="">
          <h4>
            Morbi vitae
          </h4>
          <p>
            October
          </p>
          <p class="py-2">
            Donec
          </p>
        </div>
        <div class="col">
          <img src="../assets/img/post_feat_img_23-320x202.jpg" alt="">
          <h4>
            Morbi vitae
          </h4>
          <p>
            October
          </p>
          <p class="py-2">
            Donec
          </p>
        </div>
      </div>
</div>
    </div>
    <!-- / ALL THE LATEST NEWS -->
  </main>
</template>

<style lang="scss" scoped>
main{
  

  #first-section{
    background-image: url(../assets/img/home_slider_bg.jpg);
    object-fit:cover;
    height: 880px;
    
    div{
    
      h1{
        color: white;
        font-size: 9rem;
      } 
      
      p{
        color: white;
        font-size: 1.9rem;
      }

      .my-btn{
        background-color: #28AFC3;
        color: white;
        font-weight: bold;
      }
    }
  }
  

  #second-section{
    background-color: #F2F2F2;
    height: 300px;

    div{

      h3{
        text-align: center;
        font-weight: bold;
        font-size: 1rem;

        padding-bottom: 20px;
      }

      p{
        text-align: center;
        font-size: 1.4rem;
      }

    }
  }

  #third-section{
    h1, p{
      text-align: center;
      font-weight: bold;
    }
    .my-underline{
      padding-bottom: 20px;
      border-bottom: 2px solid #ff8d61;
      line-height: 48px;
    }
  }
}
</style>
