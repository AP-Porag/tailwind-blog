<template>
  <div class="">
    <!-- post view -->
    <div class="rounded-sm overflow-hidden bg-white shadow-sm">
      <div class="">
        <img src="~/assets/images/post-1.jpg" class="w-full h-96 object-cover">
      </div>
      <div class="p-4 pb-5">
        <h2 class="block text-2xl font-semibold text-gray-700 font-roboto">
          Lorem, ipsum dolor sit amet consectetur adipisicing elit. Iddo loremque, totam
          architecto odit pariatur Lorem ips dolor.
        </h2>
        <div class="mt-2 flex space-x-4">
          <div class="flex text-gray-400 text-sm items-center">
                                <span class="mr-2 text-xs">
                                    <i class="far fa-user"></i>
                                </span>
            Blogging Tips
          </div>
          <div class="flex text-gray-400 text-sm items-center">
                                <span class="mr-2 text-xs">
                                    <i class="far fa-clock"></i>
                                </span>
            June 11, 2021
          </div>
        </div>

        <p class="text-gray-500 text-sm mt-5">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Blanditiis et sunt saepe accusamus
          eum ex sint est neque provident tempore, minus laborum repudiandae vitae temporibus
          nesciunt, sed enim quo harum a id, alias maiores! Incidunt iusto minus explicabo itaque iure
          recusandae
        </p>

        <p class="bg-green-50 border border-green-500 p-3 text-sm  mt-5">
          <span class="text-xl mr-1 text-gray-400"><i class="fas fa-quote-left"></i></span>
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Doloribus blanditiis earum nam,
          quisquam magnam aut odio aliquam inventore quibusdam mollitia! Alias, mollitia eveniet iure
          quidem natus quis assumenda consectetur beatae.
          Lorem, ipsum dolor quibusdam.
          <span class="text-xl ml-1 text-gray-400"><i class="fas fa-quote-right"></i></span>
        </p>

        <p class="text-gray-500 text-sm mt-5">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Blanditiis et sunt saepe accusamus
          eum ex sint est neque provident tempore, minus laborum repudiandae vitae temporibus
          nesciunt, sed enim quo harum a id, alias maiores! Incidunt iusto minus explicabo itaque iure
          recusandae
        </p>

        <ul class="mt-6 pl-5  space-y-2">
          <li class="text-sm">
            <span class="mr-1"><i class="fas fa-angle-right"></i></span>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Perspiciatis.
          </li>
          <li class="text-sm">
            <span class="mr-1"><i class="fas fa-angle-right"></i></span>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Perspiciatis.
          </li>
          <li class="text-sm">
            <span class="mr-1"><i class="fas fa-angle-right"></i></span>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Perspiciatis.
          </li>
          <li class="text-sm">
            <span class="mr-1"><i class="fas fa-angle-right"></i></span>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Perspiciatis.
          </li>
        </ul>

        <p class="text-gray-500 text-sm mt-5">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Blanditiis et sunt saepe accusamus
          eum ex sint est neque provident tempore, minus laborum repudiandae vitae temporibus
          nesciunt, sed enim quo harum a id, alias maiores! Incidunt iusto minus explicabo itaque iure
          recusandae
        </p>

        <p class="text-gray-500 text-sm mt-5">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Blanditiis et sunt saepe accusamus
          eum ex sint est neque provident tempore, minus laborum repudiandae vitae temporibus
          nesciunt, sed enim quo harum a id, alias maiores! Incidunt iusto minus explicabo itaque iure
          recusandae
        </p>

        <div class="flex items-center flex-wrap gap-2 mt-5">
          <a href="#"
             class="px-3 py-1  text-sm border border-gray-200 rounded-sm transition hover:bg-blue-500 hover:text-white">Beauti</a>
          <a href="#"
             class="px-3 py-1  text-sm border border-gray-200 rounded-sm transition hover:bg-blue-500 hover:text-white">Sports</a>
          <a href="#"
             class="px-3 py-1  text-sm border border-gray-200 rounded-sm transition hover:bg-blue-500 hover:text-white">Business</a>
        </div>

        <div class="mt-5 pt-5 border-t border-gray-200 flex gap-2">
          <a href="#"
             class="w-8 h-8 rounded-sm flex items-center justify-center border border-gray-400 text-base text-gray-800">
            <i class="fab fa-facebook-f"></i>
          </a>
          <a href="#"
             class="w-8 h-8 rounded-sm flex items-center justify-center border border-gray-400 text-base text-gray-800">
            <i class="fab fa-twitter"></i>
          </a>
          <a href="#"
             class="w-8 h-8 rounded-sm flex items-center justify-center border border-gray-400 text-base text-gray-800">
            <i class="fab fa-instagram"></i>
          </a>
          <a href="#"
             class="w-8 h-8 rounded-sm flex items-center justify-center border border-gray-400 text-base text-gray-800">
            <i class="fab fa-pinterest-p"></i>
          </a>
          <a href="#"
             class="w-8 h-8 rounded-sm flex items-center justify-center border border-gray-400 text-base text-gray-800">
            <i class="fab fa-linkedin-in"></i>
          </a>
        </div>
      </div>
    </div>

    <!-- title -->
    <div class="flex bg-white px-3 py-2 justify-between items-center rounded-sm mt-8">
      <h5 class="text-base uppercase font-semibold font-roboto">Related post</h5>
      <NuxtLink to="#"
         class="text-white py-1 px-3 rounded-sm uppercase text-sm bg-blue-500 border border-blue-500 hover:text-blue-500 hover:bg-transparent transition">
        see more
      </NuxtLink>
    </div>

    <!-- similer post -->
    <div class="grid md:grid-cols-2 lg:grid-cols-3 grid-cols-1 gap-2 mt-4">
      <div class="rounded-sm bg-white p-3 pb-5 shadow-sm">
        <NuxtLink to="#" class="block rounded-md overflow-hidden">
          <img src="~/assets/images/img-7.jpg"
               class="w-full h-40 object-cover transform hover:scale-110 transition duration-500">
        </NuxtLink>
        <div class="mt-3">
          <NuxtLink to="#">
            <h2
              class="block text-base font-semibold text-gray-700 hover:text-blue-500 transition font-roboto">
              Lorem, ipsum dolor amet sit consec tetur elit.
            </h2>
          </NuxtLink>
          <div class="mt-2 flex space-x-3">
            <div class="flex text-gray-400 text-xs items-center">
                                    <span class="mr-1 text-xs">
                                        <i class="far fa-user"></i>
                                    </span>
              Blogging Tips
            </div>
            <div class="flex text-gray-400 text-xs items-center">
                                    <span class="mr-1 text-xs">
                                        <i class="far fa-clock"></i>
                                    </span>
              June 11, 2021
            </div>
          </div>
        </div>
      </div>
      <div class="rounded-sm bg-white p-3 pb-5 shadow-sm">
        <NuxtLink to="#" class="block rounded-md overflow-hidden">
          <img src="~/assets/images/img-5.jpg"
               class="w-full h-40 object-cover transform hover:scale-110 transition duration-500">
        </NuxtLink>
        <div class="mt-3">
          <NuxtLink to="#">
            <h2
              class="block text-base font-semibold text-gray-700 hover:text-blue-500 transition font-roboto">
              Lorem, ipsum dolor amet sit consec tetur elit.
            </h2>
          </NuxtLink>
          <div class="mt-2 flex space-x-3">
            <div class="flex text-gray-400 text-xs items-center">
                                    <span class="mr-1 text-xs">
                                        <i class="far fa-user"></i>
                                    </span>
              Blogging Tips
            </div>
            <div class="flex text-gray-400 text-xs items-center">
                                    <span class="mr-1 text-xs">
                                        <i class="far fa-clock"></i>
                                    </span>
              June 11, 2021
            </div>
          </div>
        </div>
      </div>
      <div class="rounded-sm bg-white p-3 pb-5 shadow-sm hidden md:block">
        <NuxtLink to="#" class="block rounded-md overflow-hidden">
          <img src="~/assets/images/img-6.jpg"
               class="w-full h-40 object-cover transform hover:scale-110 transition duration-500">
        </NuxtLink>
        <div class="mt-3">
          <NuxtLink to="#">
            <h2
              class="block text-base font-semibold text-gray-700 hover:text-blue-500 transition font-roboto">
              Lorem, ipsum dolor amet sit consec tetur elit.
            </h2>
          </NuxtLink>
          <div class="mt-2 flex space-x-3">
            <div class="flex text-gray-400 text-xs items-center">
                                    <span class="mr-1 text-xs">
                                        <i class="far fa-user"></i>
                                    </span>
              Blogging Tips
            </div>
            <div class="flex text-gray-400 text-xs items-center">
                                    <span class="mr-1 text-xs">
                                        <i class="far fa-clock"></i>
                                    </span>
              June 11, 2021
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- comment -->
    <div class="p-4 bg-white rounded-sm shadow-sm mt-8">
      <h4 class="text-base uppercase  font-semibold mb-4 font-roboto">Post a comment</h4>
      <p class="text-sm text-gray-500 mb-4">12 comments</p>

      <div class="space-y-5">
        <div class="flex items-start border-b  pb-5 border-gray-200">
          <div class="w-12 h-12 flex-shrink-0">
            <img src="~/assets/images/avatar.png" class="w-full">
          </div>
          <div class="flex-grow pl-4">
            <h4 class="text-base  font-roboto">Rasel Ahmed</h4>
            <p class="text-xs text-gray-400">9 Aprile 2021 at 12:34 AM</p>
            <p class="text-sm font-600 mt-2">Great article. Thanks</p>
            <div class="flex gap-2 mt-2">
              <button
                class="text-gray-500 px-1 text-xs border border-gray-200 rounded-sm shadow-sm hover:bg-blue-500 hover:text-white transition">Reply</button>
              <button
                class="text-gray-500 px-1 text-xs border border-gray-200 rounded-sm shadow-sm hover:bg-blue-500 hover:text-white transition">Delete</button>
            </div>
          </div>
        </div>
        <div class="flex items-start border-b  pb-5 border-gray-200">
          <div class="w-12 h-12 flex-shrink-0">
            <img src="~/assets/images/avatar-2.png" class="w-full">
          </div>
          <div class="flex-grow pl-4">
            <h4 class="text-base  font-roboto">John Doe</h4>
            <p class="text-xs text-gray-400">9 Aprile 2021 at 12:34 AM</p>
            <p class="text-sm font-600 mt-2">Great article. Thanks</p>
            <div class="flex gap-2 mt-2">
              <button
                class="text-gray-500 px-1 text-xs border border-gray-200 rounded-sm shadow-sm hover:bg-blue-500 hover:text-white transition">Reply</button>
              <button
                class="text-gray-500 px-1 text-xs border border-gray-200 rounded-sm shadow-sm hover:bg-blue-500 hover:text-white transition">Delete</button>
            </div>
          </div>
        </div>
        <div class="flex items-start">
          <div class="w-12 h-12 flex-shrink-0">
            <img src="~/assets/images/avatar.png" class="w-full">
          </div>
          <div class="flex-grow pl-4">
            <h4 class="text-base  font-roboto">Rasel Ahmed</h4>
            <p class="text-xs text-gray-400">9 Aprile 2021 at 12:34 AM</p>
            <p class="text-sm font-600 mt-2">Great article. Thanks</p>
            <div class="flex gap-2 mt-2">
              <button
                class="text-gray-500 px-1 text-xs border border-gray-200 rounded-sm shadow-sm hover:bg-blue-500 hover:text-white transition">Reply</button>
              <button
                class="text-gray-500 px-1 text-xs border border-gray-200 rounded-sm shadow-sm hover:bg-blue-500 hover:text-white transition">Delete</button>
            </div>
          </div>
        </div>
      </div>

      <form action="#" class="mt-8">
        <h5 class="text-base  mb-1">Comment:</h5>
        <textarea type="text"
                  class="w-full border border-gray-200 py-3 px-5 text-sm  rounded-sm h-20 focus:outline-none focus:border-gray-400"
                  placeholder="type your comment"></textarea>
        <div class="mt-2">
          <butotn type="submit"
                  class="text-white py-1 px-3 rounded-sm uppercase text-sm bg-blue-500 border border-blue-500 hover:text-blue-500 hover:bg-transparent transition">
            Submit
          </butotn>
        </div>
      </form>
    </div>
  </div>
</template>

<script>
export default {
  name: "_id"
}
</script>

<style scoped>

</style>
