<template>
  <div class="about-page">
    <div class="container mx-auto px-4">
      <div class="">
        <div class="image-box">
          <!-- Website Logo -->
          <div class="content">
            <h2>Hi there,</h2>
            <img class="image" src="~/assets/images/about-hero.png">

            <h3>Let's talk about this app</h3>
          </div>
        </div>
        <div class="info-box">
          <div class="info bg-white shadow-sm rounded-sm px-4 py-4 mb-6">
            <h1 class="section-header text-xl text-blue-500 mb-4">Project Name</h1>
            <p><a href="https://tail-blog.asrafporag.me/">Tail-Blog</a></p>
          </div>
          <div class="info info bg-white shadow-sm rounded-sm px-4 py-4 mb-6">
            <h1 class="section-header text-xl text-blue-500 mb-4">Project Description</h1>
            <p>The Tail Blog is a application for blogging.This website design with Tailwind CSS.I used Nuxt Js for frontend framework.All element are design by Tailwind CSS.</p>
          </div>
          <div class="pt-8 grid grid-cols-1 sm:grid-cols-1 md:grid-cols-2 lg:grid-cols-2 gap-8 pb-16 info bg-white shadow-sm rounded-sm px-4 py-4">

            <div class="item">
              <h1 class="section-header text-xl text-blue-500 mb-4">Framework</h1>
              <div class="">
                <ul>
                  <li>
                    <p>Nuxt js (Frontend)</p>
                  </li>
                </ul>
              </div>
            </div>

            <div class="item">
              <h1 class="section-header text-xl text-blue-500 mb-4">Document Object Model (DOM)</h1>
              <div class="">
                <ul>
                  <li>
                    <p>HTML5</p>
                  </li>
                  <li>
                    <p>CSS3</p>
                  </li>
                  <li>
                    <p>Javascript</p>
                  </li>
                  <li>
                    <p>Tailwind CSS</p>
                  </li>
                </ul>
              </div>
            </div>

            <div class="item">
              <h1 class="section-header text-xl text-blue-500 mb-4">Hosting</h1>
              <div class="">
                <ul>
                  <li>
                    <p>Cpanel</p>
                  </li>
                </ul>
              </div>
            </div>

          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "index"
}
</script>

<style scoped>
.about-page{
  padding-top: 70px;
  box-sizing: border-box;
  width: 100%;
  background-image: url(assets/images/about-bg.svg);
  background-position: center -250px;
  background-repeat: no-repeat;
  position: relative;
  top: 0;
  left: 0;
  z-index: 2;
}
.content{
  color: #494949;
  padding: 20px 0 70px 0;
  width: 800px;
  margin: 0 auto;
  text-align: center;
}
.content h2{
  height: 233px;
  line-height: 233px;
  font-family: 'Shrikhand', cursive;
  font-size: 10em;
  font-weight: 400;
  position: relative;
  top: 0;
  left: 0;
  text-transform: capitalize;
}
.content img{
  position: relative;
  top: 0;
  left: 0;
  margin-top: -140px;
  width: 710px;
}
.content h3{
  font-size: 4em;
  margin-top: 40px;
  margin-bottom: 20px;
  font-weight: 700;
  text-transform: capitalize;
}
@media (min-width:320px) and (max-width:575px) {
  .content{
    width: auto;
  }
  .content h2{
    font-size: 5em;
  }
  .content h3{
    font-size: 1em;
  }
  .content .image{
    width: 335px;
    height: auto;
  }
}
@media (min-width:576px) and (max-width:767px) {
  .content{
    width: auto;
  }
  .content h2{
    font-size: 7em;
  }
  .content h3{
    font-size: 2em;
  }
  .content .image{
    width: 610px;
    height: auto;
  }
}

</style>
