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
    <div id="third-section">
      <div class="py-5">
        <P>PHASELLUS EGET METUS</P>
        <h1>
          All the <span class="my-underline">latest</span> news
        </h1>
      </div>
      <div class="container py-5">
        <div class="row">
          <div class="col-4 d-flex flex-column  text-start">
            <img src="../assets/img/post_feat_img_25-320x202.jpg" alt="">
            <h2 class="fw-bolder fs-6 text-start py-2">
              Morbi vitae dui euismod vulputate sollicitudin
            </h2>
            <p class="text-start my-p">
              October 11th, 2015 | <span>2 comments</span>
            </p>
            <p class="py-2 text-start">
              Donec finibus sit amet orci eget ultricies. Praesent posuere ante ut erat fringilla, vestibulum placerat metus mattis. Aenean dictum vitae nisl
            </p>
          </div>
          <div class="col-4 d-flex flex-column  text-start">
            <img src="../assets/img/post_feat_img_24-320x202.jpg" alt="">
            <h2 class="fw-bold fs-6 py-2">
              Vivamus pellenteque, felis quis varius
            </h2>
            <p class="text-start my-p">
              October 11th, 2015 | Comments Off
            </p>
            <p class="py-2 text-start">
              Donec finibus sit amet orci eget ultricies. Praesent posuere ante ut erat fringilla, vestibulum placerat metus mattis. Aenean dictum vitae nisl
            </p>
          </div>
          <div class="col-4 d-flex flex-column  text-start">
            <img src="../assets/img/post_feat_img_23-320x202.jpg" alt="">
            <h2 class="fw-bold fs-6 py-2">
              Donec ornare pretium eget scelisque justo
            </h2>
            <p class="text-start my-p">
              October 11th, 2015 | Comments Off
            </p>
            <p class="py-2 text-start">
              Donec finibus sit amet orci eget ultricies. Praesent posuere ante ut erat fringilla, vestibulum placerat metus mattis. Aenean dictum vitae nisl
            </p>
          </div>
        </div>
      </div>
      <!-- FEATURED ARTICLE -->
      <div id="fetured-article" class="container d-flex flex-column justify-content-end align-items-start">
        
        <p class=" text-start py-3 fs-4">
          FEATURED ARTICLE
        </p>
        <h1 class= "text-start">
          Cras malesuada et orci eget pharetra
        </h1>
        <p class="text-start py-4">
          in quis lectus sed leo elementum faucibus in dapibus dictum. Nullamolestie tortor nec lectus venenatis, sed blandit dui, dolor at bibendum sadips ets ipsums dolores ficilis uns leo lectus.
        </p>
        <button class="btn py-3 px-5 rounded-1" type="button">
          READ MORE >
        </button>
      </div>
      <!-- /FEATURED ARTICLE -->
      <div class="container py-5">
        <div class="row">
          <div class="col-4 d-flex flex-column  text-start">
            <img src="../assets/img/post_feat_img_22-320x202.jpg" alt="">
            <h2 class="fw-bolder fs-6 text-start py-2">
              Fusce sollicitudin nunc sed placerat varius
            </h2>
            <p class="text-start my-p">
              October 11th, 2015 | Comments Off
            </p>
            <p class="py-2 text-start">
              Donec finibus sit amet orci eget ultricies. Praesent posuere ante ut erat fringilla, vestibulum placerat metus mattis. Aenean dictum vitae nisl
            </p>
          </div>
          <div class="col-4 d-flex flex-column  text-start">
            <img src="../assets/img/post_feat_img_21-320x202.jpg" alt="">
            <h2 class="fw-bold fs-6 py-2">
              Donec facilis sodales leo sit amet laoreet
            </h2>
            <p class="text-start my-p">
              October 11th, 2015 | Comments Off
            </p>
            <p class="py-2 text-start">
              Donec finibus sit amet orci eget ultricies. Praesent posuere ante ut erat fringilla, vestibulum placerat metus mattis. Aenean dictum vitae nisl
            </p>
          </div>
          <div class="col-4 d-flex flex-column  text-start">
            <img src="../assets/img/post_feat_img_20-320x202.jpg" alt="">
            <h2 class="fw-bold fs-6 py-2">
              Proin eu purus sed aru aliquet curabir vens
            </h2>
            <p class="text-start my-p">
              October 11th, 2015 | Comments Off
            </p>
            <p class="py-2 text-start">
              Donec finibus sit amet orci eget ultricies. Praesent posuere ante ut erat fringilla, vestibulum placerat metus mattis. Aenean dictum vitae nisl
            </p>
          </div>
        </div>
      </div>
      <!-- REVIEWED PRODUCT // TUTORIALS & GUIDES -->
      <div class="container py-5">
        <div class="row">
          <div id="reviewed-product" class="col-8">
            <p class=" text-start py-3 fs-4">
              REVIEWED PRODUCT
            </p>
            <h1 class= "text-start">
              Mauris viverra atisan ipsum eget felis prims efficitur varius
            </h1>
            <p class="text-start py-4">
              in quis lectus sed leo elementum faucibus in dapibus dictum. Nullamolestie tortor nec lectus venenatis, sed blandit dui, dolor at bibendum.
            </p>
            <button class="btn py-3 px-5 rounded-1" type="button">
              READ MORE >
            </button>
          </div>
          <!-- TUTORIALS & GUIDES -->
          <div id="tutorials" class="col-4 d-flex flex-column justify-content-around px-4">
            <h2 class="fw-bold">
              <span class="my-underline">Tutorials</span> & Guides
            </h2>
            <div class="d-flex">
              <img src="../assets/img/post_feat_img_23-147x118.jpg" alt="">
              <div class="d-flex flex-column px-3">
                <h2 class="fw-bold fs-6 py-2">
                  Donec ornare pretium eget scelisque justo
                </h2>
                <p class="text-start mini-p">
                  October 11th, 2015 | Comments Off
                </p>
              </div>
            </div>
            <div class="d-flex">
              <img src="../assets/img/post_feat_img_22-147x118.jpg" alt="">
              <div class="d-flex flex-column px-3">
                <h2 class="fw-bolder fs-6 text-start py-2">
                  Fusce sollicitudin nunc sed placerat varius
                </h2>
                <p class="text-start mini-p">
                  October 11th, 2015 | Comments Off
                </p>
              </div>
            </div>
            <div class="d-flex">
              <img src="../assets/img/post_feat_img_20-147x118.jpg" alt="">
              <div class="d-flex flex-column px-3">
                <h2 class="fw-bold fs-6 py-2">
                  Proin eu purus sed aru aliquet curabir vens
                </h2>
                <p class="text-start mini-p">
                  October 11th, 2015 | Comments Off
                </p>
              </div>
            </div>
          </div>
          <!-- /TUTORIALS & GUIDES -->
        </div>
      </div>
      <!-- /REVIEWED PRODUCT // TUTORIALS & GUIDES -->
    </div>
    <!-- / ALL THE LATEST NEWS -->
    <!-- READ OUR BLOG -->
    <div id="read-blog" class="fw-bold d-flex justify-content-center align-items-center">
      READ OUR BLOG →
    </div>
    <!-- /READ OUR BLOG -->

    <!-- FORUM SECTION -->
    <div id="forum-section">
      <div class="container">
        <div class="py-5 text-center">
          <P>PHASELLUS EGET METUS</P>
          <h1 class="fw-bold">
            Foru<span class="my-underline">m Se</span>ctions
          </h1>
        </div>
        <div>
          <div class="row row-cols-4 py-4 d-flex justify-content-center gap-5">
            <div class="col-2 d-flex flex-column align-items-center my-bg py-5">
              <div class="my-bg-icon rounded-circle d-flex justify-content-center align-items-center">
                <font-awesome-icon icon="fa-solid fa-file-lines" />
              </div>
              <div class="d-flex justify-content-center">
                <h5 class="fw-bold py-2">
                  News & Community
                </h5>
              </div>
            </div>
            <div class="col-2 d-flex flex-column align-items-center my-bg py-5">
              <div class="my-bg-icon rounded-circle d-flex justify-content-center align-items-center">
                <font-awesome-icon icon="fa-brands fa-apple" />
              </div>
              <div class="d-flex justify-content-center">
                <h5 class="fw-bold py-2">
                  Apple Forum
                </h5>
              </div>
            </div>
            <div class="col-2 d-flex flex-column align-items-center my-bg py-5">
              <div class="my-bg-icon rounded-circle d-flex justify-content-center align-items-center">
                <font-awesome-icon icon="fa-brands fa-windows" />
              </div>
              <div class="d-flex justify-content-center">
                <h5 class="fw-bold py-2">
                  Microsoft Forum
                </h5>
              </div>
            </div>
            <div class="col-2 d-flex flex-column align-items-center my-bg py-5">
              <div class="my-bg-icon rounded-circle d-flex justify-content-center align-items-center">
                <font-awesome-icon icon="fa-brands fa-android" />
              </div>
              <div class="d-flex justify-content-center">
                <h5 class="fw-bold py-2">
                  Android Forum
                </h5>
              </div>
            </div>
          </div>
          <!-- seconda parte -->
          <div class="row row-cols-4 py-4 d-flex justify-content-center gap-5">
            <div class="col-2 d-flex flex-column align-items-center my-bg py-5">
              <div class="my-bg-icon rounded-circle d-flex justify-content-center align-items-center">
                <font-awesome-icon icon="fa-solid fa-mug-saucer" />
              </div>
              <div class="d-flex justify-content-center">
                <h5 class="fw-bold py-2">
                  General Discussion
                </h5>
              </div>
            </div>
            <div class="col-2 d-flex flex-column align-items-center my-bg py-5">
              <div class="my-bg-icon rounded-circle d-flex justify-content-center align-items-center">
                <font-awesome-icon icon="fa-solid fa-cubes" />
              </div>
              <div class="d-flex justify-content-center">
                <h5 class="fw-bold py-2">
                  Apps & Software
                </h5>
              </div>
            </div>
            <div class="col-2 d-flex flex-column align-items-center my-bg py-5">
              <div class="my-bg-icon rounded-circle d-flex justify-content-center align-items-center">
                <font-awesome-icon icon="fa-solid fa-laptop" />
              </div>
              <div class="d-flex justify-content-center">
                <h5 class="fw-bold py-2">
                  Gadget & Stuff
                </h5>
              </div>
            </div>
            <div class="col-2 d-flex flex-column align-items-center my-bg py-5">
              <div class="my-bg-icon rounded-circle d-flex justify-content-center align-items-center">
                <font-awesome-icon icon="fa-solid fa-wrench" />
              </div>
              <div class="d-flex justify-content-center">
                <h5 class="fw-bold py-2">
                  Tutorials & Guides
                </h5>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- /FORUM SECTION -->
    <!-- GO TO FORUM -->
    <div id="read-blog" class="fw-bold d-flex justify-content-center align-items-center">
      GO TO FORUM →
    </div>
    <!-- /GO TO FORUM -->
    <!-- COMMUNITY -->
    <div id="community" class="text-center d-flex flex-column justify-content-center align-items-center">
      <div class="container">
        <h1>
          Hey! Join to our <br>
          Community
        </h1>
        <p class="py-4">
          Nulla molestie tortor nec lectus venenatis, sed blandit dui finibus. Curabitur feugiat <br>
          vulputate purus ipsums dolores ficilis uns etra.
        </p>
        <button class="btn py-3 px-5 rounded-1 fw-bold" type="button">
          SIGN UP >
        </button>
      </div>
    </div>
    <!-- /COMMUNITY -->
  </main>
</template>

<style lang="scss" scoped>
main{
  

  #first-section{
    background-image: url(../assets/img/home_slider_bg.jpg);
    background-size: cover;
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
    .row{
      .my-p{
          font-size: 0.9rem;
        }
      p{
        color: #707070;
        font-weight: normal;
        
        span{
          color: black;
          font-weight: bold;
        }
      }
      .col{
        

        img{
          width: 100%;
        }
        
      }
    }

    #fetured-article{
      background-image: url(../assets/img/featured_article_1_bg.jpg);
      background-size: cover;
      object-fit: cover;
      height: 650px;
      color: white;
      padding: 90px;

      button{
        background-color: black;
        color: white;
        font-weight: bold;
      }
    }

    #reviewed-product{
      background-image: url(../assets/img/featured_article_2_bg.jpg);
      background-size: cover;
      height: 550px;
      color: white;
      padding: 125px;

      p{
        color: white;
      }

      button{
        background-color: black;
        color: white;
        font-weight: bold;
      }
    }

    #tutorials{
      .mini-p{
        font-size: 0.8rem;
      }
    }
  }

  #read-blog{
    background-color: #191919;
    height: 150px;
    color: white;
  }

  #forum-section{
    background-color: #f2f2f2;
    .my-underline{
      padding-bottom: 20px;
      border-bottom: 2px solid #ff8d61;
      line-height: 48px;
    }

    .my-bg-icon{
      font-size: 3rem;
      color: white;
      background-color: #ff8d61;
      height: 90px;
      width: 90px;
    }
    
    .my-bg{
      background-color: white;
      border-top-style: solid;
      border-top-color: #28AFC3;
    }
  }

  #community{
    background-image: url(../assets/img/join_now_cta_bg.jpg);
    height: 600px;
    color: white;

    button{
      color: white;
      background-color: #28AFC3;
    }
  }
}
</style>
