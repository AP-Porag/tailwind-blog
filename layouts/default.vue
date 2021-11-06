<template>
<div class="">
  <NavBar/>
  <main class="py-12 bg-gray-100 min-h-screen">
    <div class="container px-4 flex mx-auto flex-wrap lg:flex-nowrap">
      <div class="w-3/12 hidden xl:block">
        <div class="bg-white shadow-sm rounded-sm p-4">
          <h3 class="text-xl font-semibold font-roboto text-gray-700 mb-3">Category</h3>
          <div class="text-gray-700 space-y-2">
            <NuxtLink :to="`/category/${category.id}`" class="flex items-center font-semibold leading-4 uppercase text-sm hover:text-blue-500 transition" v-for="category in categories" :key="category.id">
              <span class="mr-2">
                <i :class="category.icon"></i>
              </span>
              <span>{{category.title}}</span>
              <span class="font-normal ml-auto">({{category.count}})</span>
            </NuxtLink>
          </div>
        </div>
        <div class="bg-white shadow-sm rounded-sm p-4 mt-4">
          <h3 class="text-xl font-semibold font-roboto text-gray-700 mb-3 capitalize">Random posts</h3>
          <div class="random_post space-y-4">
            <NuxtLink :to="`/post/${random.id}`" class="flex group" v-for="random in randoms" :key="random.id">
              <div class="flex-shrink-0">
                <img :src="require(`~/assets/images/${random.thumbnail}`)" :alt="random.title" class="w-20 h-14 rounded object-cover">
              </div>
              <div class="flex-grow pl-3">
                <h5 class="text-md leading-5 font-roboto font-semibold capitalize group-hover:text-blue-500 transition">{{random.title}}</h5>
                <div class="flex text-gray-400 text-sm items-center">
                <span class="mr-1 text-xs">
                  <i class="far fa-clock"></i>
                </span>
                  {{random.date}}
                </div>
              </div>
            </NuxtLink>
          </div>
        </div>
      </div>
      <div class="xl:w-6/12 lg:mx-6 lg:w-8/12 w-full">
        <Nuxt/>
      </div>
      <div class="xl:w-3/12 lg:w-4/12 w-full mt-8 lg:mt-0">
        <div class="bg-white shadow-sm rounded-sm p-4">
          <h3 class="text-xl font-semibold font-roboto text-gray-700 mb-3 capitalize">Social Plugin</h3>
          <div class="flex gap-2">
            <a href="#" class="w-8 h-8 rounded-sm flex items-center justify-center border border-gray-400 text-base text-gray-800 hover:text-blue-500 hover:border-blue-500 transition" target="_blank">
              <i class="fab fa-facebook-f"></i>
            </a>
            <a href="#" class="w-8 h-8 rounded-sm flex items-center justify-center border border-gray-400 text-base text-gray-800 hover:text-blue-500 hover:border-blue-500 transition" target="_blank">
              <i class="fab fa-twitter"></i>
            </a>
            <a href="#" class="w-8 h-8 rounded-sm flex items-center justify-center border border-gray-400 text-base text-gray-800 hover:text-blue-500 hover:border-blue-500 transition" target="_blank">
              <i class="fab fa-instagram"></i>
            </a>
            <a href="#" class="w-8 h-8 rounded-sm flex items-center justify-center border border-gray-400 text-base text-gray-800 hover:text-blue-500 hover:border-blue-500 transition" target="_blank">
              <i class="fab fa-pinterest-p"></i>
            </a>
            <a href="#" class="w-8 h-8 rounded-sm flex items-center justify-center border border-gray-400 text-base text-gray-800 hover:text-blue-500 hover:border-blue-500 transition" target="_blank">
              <i class="fab fa-linkedin-in"></i>
            </a>
          </div>
        </div>
        <div class="bg-white shadow-sm rounded-sm p-4 mt-4">
          <h3 class="text-xl font-semibold font-roboto text-gray-700 mb-3 capitalize">Popular posts</h3>
          <div class="random_post space-y-4">
            <NuxtLink :to="`/post/${popular.id}`" class="flex group" v-for="popular in popular_posts" :key="popular.id">
              <div class="flex-shrink-0">
                <img :src="require(`~/assets/images/${popular.thumbnail}`)" :alt="popular.title" class="w-20 h-14 rounded object-cover">
              </div>
              <div class="flex-grow pl-3">
                <h5 class="text-md leading-5 font-roboto font-semibold capitalize group-hover:text-blue-500 transition">{{popular.title}}</h5>
                <div class="flex text-gray-400 text-sm items-center">
                <span class="mr-1 text-xs">
                  <i class="far fa-clock"></i>
                </span>
                  {{popular.date}}
                </div>
              </div>
            </NuxtLink>
          </div>
        </div>
        <div class="w-full bg-white shadow-sm rounded-sm p-4  mt-8">
          <h3 class="text-xl font-semibold text-gray-700 mb-3 font-roboto">Tags</h3>
          <div class="flex items-center flex-wrap gap-2">
            <a href="#"
               class="px-3 py-1  text-sm border border-gray-200 rounded-sm transition hover:bg-blue-500 hover:text-white">Beauti</a>
            <a href="#"
               class="px-3 py-1  text-sm border border-gray-200 rounded-sm transition hover:bg-blue-500 hover:text-white">Sports</a>
            <a href="#"
               class="px-3 py-1  text-sm border border-gray-200 rounded-sm transition hover:bg-blue-500 hover:text-white">Business</a>
            <a href="#"
               class="px-3 py-1  text-sm border border-gray-200 rounded-sm transition hover:bg-blue-500 hover:text-white">Politics</a>
            <a href="#"
               class="px-3 py-1  text-sm border border-gray-200 rounded-sm transition hover:bg-blue-500 hover:text-white">Computer</a>
            <a href="#"
               class="px-3 py-1  text-sm border border-gray-200 rounded-sm transition hover:bg-blue-500 hover:text-white">Coding</a>
            <a href="#"
               class="px-3 py-1  text-sm border border-gray-200 rounded-sm transition hover:bg-blue-500 hover:text-white">Web
              Design</a>
            <a href="#"
               class="px-3 py-1  text-sm border border-gray-200 rounded-sm transition hover:bg-blue-500 hover:text-white">Web
              App</a>
          </div>
        </div>
      </div>
    </div>
  </main>
  <Footer/>
</div>
</template>

<script>
import NavBar from "~/components/NavBar";
export default {
  name: "default",
  components: {NavBar},
  data(){
    return{
      categories:[
        {id:1,title:'beauty',icon:'far fa-folder-open',count:'12'},
        {id:2,title:'Business',icon:'far fa-folder-open',count:'8'},
        {id:3,title:'Fashion',icon:'far fa-folder-open',count:'4'},
        {id:4,title:'Food',icon:'far fa-folder-open',count:'17'},
        {id:5,title:'Learn',icon:'far fa-folder-open',count:'23'},
        {id:6,title:'Music',icon:'far fa-folder-open',count:'15'},
        {id:7,title:'nature',icon:'far fa-folder-open',count:'7'},
        {id:8,title:'people',icon:'far fa-folder-open',count:'13'},
        {id:9,title:'sports',icon:'far fa-folder-open',count:'3'},
        {id:9,title:'Technology',icon:'far fa-folder-open',count:'10'},
      ],
      randoms:[
        {id:32,title:'Team Bitbose geared up to attend blockchain',thumbnail:'img-1.jpg',date:'june 11, 2021'},
        {id:5,title:'After a caribbean hurricane,the battle',thumbnail:'img-2.jpg',date:'march 27, 2021'},
        {id:6,title:'California sherifs deputy shot during ambush',thumbnail:'img-3.jpg',date:'April 17, 2021'},
      ],
      popular_posts:[
        {id:32,title:'Team Bitbose geared up to attend blockchain',thumbnail:'img-4.jpg',date:'june 11, 2021'},
        {id:5,title:'After a caribbean hurricane,the battle',thumbnail:'img-5.jpg',date:'march 27, 2021'},
        {id:6,title:'California sherifs deputy shot during ambush',thumbnail:'img-6.jpg',date:'April 17, 2021'},
      ],
    }
  }
}
</script>

<style scoped>

</style>
