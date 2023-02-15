<script>
export default{
  name: 'AppFooter',
  data(){
    return{
        topics:[
            {
                title: 'POPULAR TOPICS',
                subtopics: [
                    {
                        title: 'Nam a dolor volutpat massa auctor semper',
                        url: '#'
                    },
                    {
                        title: 'Sed euismod nunc urna fermentum arcu dapibus fringilla',
                        url: '#'
                    },
                    {
                        title: 'Cras lacinia tellus id mauris finibus lacus molestie',
                        url: '#'
                    },
                    {
                        title: 'Caribus a scelerisque ligula',
                        url: '#'
                    }
                ]
            },
           {
                title: 'RECENT TOPICS',
                subtopics: [
                    {
                        title: 'Cras lacinia tellus id mauris finibus lacus molestie',
                        url: '#'
                    },
                    {
                        title: 'Proin at ligula sagittis vestibulum nisi vitae',
                        url: '#'
                    },
                    {
                        title: 'Sed nec metus at est tincidunt elementum',
                        url: '#'
                    },
                    {
                        title: 'Nulla egestas nulla eu nulla suscipit molestie',
                        url: '#'
                    }
                ]
            },
            {
                title: 'LASTEST REPLIES',
                subtopics: [
                    {
                        title: 'Cras lacinia tellus id mauris finibus lacus molestie',
                        url: '#'
                    },
                    {
                        title: 'Cras lacinia tellus id mauris finibus lacus molestie',
                        url: '#'
                    },
                    {
                        title: 'Nulla egestas nulla eu nulla suscipit molestie',
                        url: '#'
                    },
                    {
                        title: 'Mauris ac nibh quis eros sagitis lacinia a et dui',
                        url: '#'
                    }
                ]
            }
        ]
    };
  },
  components:{

  },
  methods:{

  }
}
</script>

<template>
  <footer>
    <!-- SUBSCRIBE -->
    <div id="subscribe" class=" d-flex justify-content-center align-items-center">
      <div class="container">
        
        <h2 class="text-center py-4">
          Subscribe to our Newsletter
        </h2>
        <div class="d-flex justify-content-center gap-3">
          <input type="email" class="form-control w-50 rounded-1" id="exampleFormControlInput1" placeholder="Insert your email*"> 
          <button class="btn py-3 px-5 rounded-1 fw-bold" type="button">
            SEND
          </button>
        </div>
      </div>
    </div>
    <!-- /SUBSCRIBE -->
    <!-- OTHER TOPICS -->
    <div id="other-topics">
      <div class="container py-5">
        <div class="row">
          <div class="col-3  py-4">
            <h4 class="fw-bold">
              AVADA TECH FORUM
            </h4>
            <p class="py-4">
              Sed semper, nisl id feugiat eleifend, erat est digssim felis, quis auctor elit enim nec ante. Cras et nibh risus. Pellentesque non mi sit amet mi intermentum.
            </p>
          </div>
          <div class="col-3 py-4" v-for="topic in topics">
            <h4>
              {{ topic.title }}
            </h4>
            <ul>
              <li class="py-2" v-for="subtopic in topic.subtopics">
                <a :href="subtopic.url">
                  {{ subtopic.title }}
                </a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
    <!-- /OTHER TOPICS -->
    <!-- SOCIAL -->
    <hr>
    <div id="social" class="d-flex justify-content-center align-items-center">
      <div class="container d-flex justify-content-between align-items-center">
        <p>
          © Copyright 2012 - 2020 | Avada Theme by <span>Theme Fusion</span> | All Rights Reserved | Powered by <span>WordPress</span>
        </p>
        <div class="d-flex gap-2">
          <div class="my-bg-icon fb rounded-circle d-flex justify-content-center align-items-center">
            <font-awesome-icon icon="fa-brands fa-facebook-f" />
          </div>
          <div class="my-bg-icon tw rounded-circle d-flex justify-content-center align-items-center">
            <font-awesome-icon icon="fa-brands fa-twitter" />
          </div>
          <div class="my-bg-icon ig rounded-circle d-flex justify-content-center align-items-center">
            <font-awesome-icon icon="fa-brands fa-instagram" />
          </div>
          <div class="my-bg-icon yt rounded-circle d-flex justify-content-center align-items-center">
            <font-awesome-icon icon="fa-brands fa-youtube" />
          </div>
        </div>
      </div>
    </div>
    <div class="d-flex justify-content-end align-items-end px-5">
        <button type="button" class="btn btn-secondary fw-bold fs-3" data-bs-toggle="dropdown" aria-expanded="false">
          ⌃
        </button>
      </div>
    <!-- /SOCIAL -->
  </footer>
</template>

<style lang="scss" scoped>
footer{

  #subscribe{
    background-color: #f2f2f2;
    height: 300px;
    

    button{
      background-color: black;
      color: white;
    }
  }

  #other-topics{
    height: 500px;

    p{
      color: #707070;
    }
    
    a{
      color: black;
      text-decoration: none;
    }
    ul{
      list-style-type: "\2B9E";
      
      li{
        border-bottom: 1px solid #707070;
      }
    }
  }

  #social{
    height: 100px;

    p{
      color: #707070;
    }

    span{
      font-weight: bold;
      color: black;
    }

    .my-bg-icon{
      font-size: 1.5rem;
      color: white;
      height: 50px;
      width: 50px;
    }
    .fb{
      background-color: #3C5998;
    }

    .tw{
      background-color: #54ACEE;
    }

    .ig{
      background-color: #3F729B;
    }
    .yt{
      background-color: #CD201F;
    }
  }

}
</style>
