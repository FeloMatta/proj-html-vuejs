<script>
export default{
  name: 'AppHeader',
  data(){
    return{
        links:[
            {
                label: 'Home',
                url: '#',
                svg: true
            },
            {
                label: 'Apple',
                url: '#',
                svg: false
            },
            {
                label: 'Microsoft',
                url: '#',
                svg: false
            },
            {
                label: 'Android',
                url: '#',
                svg: false
            },
            {
                label: 'Forums',
                url: '#',
                svg: false
            },
            {
                label: 'Contact us',
                url: '#',
                svg: false
            },
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
    <header>
        <div class="container d-flex justify-content-between align-items-center">
            <img class="py-2" src="../assets/img/logo.png" alt="LOGO">
            <ul class="d-flex align-items-center">
                <li class="px-3" v-for="link in links">
                    <a :href="link.url">
                        <button type="button" class="btn py-4 position-relative">
                                {{ link.label }} <svg v-if="link.svg" width="1em" height="1em" viewBox="0 0 16 16" class="position-absolute  start-50 translate-middle mt-1" fill="#28AFC3" xmlns="http://www.w3.org/2000/svg"><path d="M7.247 11.14L2.451 5.658C1.885 5.013 2.345 4 3.204 4h9.592a1 1 0 0 1 .753 1.659l-4.796 5.48a1 1 0 0 1-1.506 0z"/></svg>
                        </button>
                    </a>
                </li>
                <li>
                    <a href="">
                        <button class="btn rounded-1 py-2 px-4 my-button" type="button">
                            JOIN US
                        </button> 
                    </a>
                </li>
                <li class="px-4">
                    <a href="">
                        <font-awesome-icon icon="fa-solid fa-magnifying-glass" />
                    </a>
                </li>
            </ul>
        </div>
    </header>
</template>

<style lang="scss" scoped>
header{
    background-color: #28AFC3;

    ul{
        list-style-type: none;
        
        li{

            a{
                color: white;

                button{
                    color: #ffffff;

                    svg{
                        bottom: -20px;
                    }
                    
                }

                .my-button{
                    font-size: 0.8rem;
                    font-style: bold;
                    background-color: #191919;
                }
            }
        }
    }
}
</style>
