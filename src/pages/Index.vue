<template>
  <Layout>
    <div class="overflow-x-hidden border-gray-200 border-b">
      <div class="get-to-know-me container-inner mx-auto text-xl pb-10 relative">
        
        <div class="flex flex-col sm:flex-column items-center mb-16">
          <div class="my-6"><g-image src="../../static/avatar.jpg" alt="avatar" class="w-32 h-32 rounded-full mb-8 lg:mb-0" /></div>
          <div class="flex-1 font-bold w-full sm:w-3/5 text-center mb-3">
            <div class="text-lg leading-tight">Hi, I am</div>
            <div class="text-4xl leading-tight text-green-500">Aaron Mercado</div>
            <div class="inline-block">
              <span class="mx-1">
                <a class="text-gray-700" href="https://github.com/ronmrcdo"><font-awesome :icon="['fab', 'github']"/></a>
              </span>
              <span class="mx-1">
                <a class="text-gray-700" href="https://www.linkedin.com/in/aaron-mercado-8153a015b/"><font-awesome :icon="['fab', 'linkedin']"/></a>
              </span>
            </div>
          </div>
          <div class="flex-1 text-lg sm:text-xl ml-6">
            I'm a full stack developer specialized in web application. I practice the habit of learning and adapting in the fast-paced changes in technology. With the use of forums, articles, and my connections to my peers, I make an interest to apply the best practices and technologies to my web development career.
          </div>
        </div>
      </div> <!-- end get-to-know me -->
    </div>

    <div class="overflow-x-hidden border-b">
      <div class="projects container-inner mx-auto text-xl border-gray-500 py-16 relative">
        <!-- <h2 class="font-bold mb-6" id="projects">Here are some projects I've worked on:</h2>

        <div class="absolute right-0" style="top: 50px; transform: translate(100%) rotate(180deg)">
          <svg width="170px" height="170px"><use xlink:href="#dots-triangle" /></svg>
        </div> -->
        <div class="hero container-inner mx-auto flex flex-col sm:flex-row justify-between mb-3">
          <div class="font-bold w-full sm:w-3/5 text-center sm:text-left">
            <div class="text-4xl leading-tight">Projects</div>
            <div class="leading-tight text-gray-600">Here are the list of project I've worked on.</div>
          </div>
          <div class="mt-8 sm:mt-0">
            <g-image src="../../static/developer.svg" alt="hero" class="mx-auto sm:mx-0" />
          </div>
        </div> <!-- end hero -->

        <ul class="text-lg sm:text-xl">
          <li class="checkmark mb-6">
            <div><a href="https://github.com/ronmrcdo/laravel-inventory">Laravel Inventory</a></div>
            <div class="text-lg text-gray-600">This is an open source package that provides the product database design and inventory with the help of built-in functions it ease the creation of product with variations</div>
            <div class="py-4">
              <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2">Laravel</span>
              <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2">Inventory</span>
              <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700">Product</span>
            </div>
          </li>
        </ul>
      </div> <!-- end projects -->

    </div>

    <div class="overflow-x-hidden">
      <div class="projects container-inner mx-auto text-xl border-gray-500 py-16 relative">
        <div class="hero container-inner mx-auto flex flex-col sm:flex-row justify-between mb-3">
          <div class="flex-1 font-bold w-full sm:w-3/5 text-center sm:text-left">
            <div class="text-4xl leading-tight">About Me</div>
            <div class="text-sm text-gray-600">I have 2 yrs+ experience developing web applications and have experience with RESTful API, Test Driven Development, and Object-Oriented Programming</div>
          </div>
        </div> <!-- end hero -->

        <ul class="text-lg sm:text-xl">
          <li>
            <div class="py-4 px-4">
              <span class="inline-block bg-gray-200 rounded-full px-3 py-1 my-2 text-sm font-semibold text-gray-700 mr-2">Angular</span>
              <span class="inline-block bg-gray-200 rounded-full px-3 py-1 my-2 text-sm font-semibold text-gray-700 mr-2">Laravel</span>
              <span class="inline-block bg-gray-200 rounded-full px-3 py-1 my-2 text-sm font-semibold text-gray-700 mr-2">VueJS / Nuxt</span>
              <span class="inline-block bg-gray-200 rounded-full px-3 py-1 my-2 text-sm font-semibold text-gray-700 mr-2">PHP</span>
              <span class="inline-block bg-gray-200 rounded-full px-3 py-1 my-2 text-sm font-semibold text-gray-700 mr-2">JavaScript</span>
              <span class="inline-block bg-gray-200 rounded-full px-3 py-1 my-2 text-sm font-semibold text-gray-700 mr-2">TypeScript</span>
              <span class="inline-block bg-gray-200 rounded-full px-3 py-1 my-2 text-sm font-semibold text-gray-700 mr-2">Docker</span>
              <span class="inline-block bg-gray-200 rounded-full px-3 py-1 my-2 text-sm font-semibold text-gray-700 mr-2">CI/CD</span>
              <span class="inline-block bg-gray-200 rounded-full px-3 py-1 my-2 text-sm font-semibold text-gray-700 mr-2">Design Patterns</span>
              <span class="inline-block bg-gray-200 rounded-full px-3 py-1 my-2 text-sm font-semibold text-gray-700 mr-2">OOP</span>
              <span class="inline-block bg-gray-200 rounded-full px-3 py-1 my-2 text-sm font-semibold text-gray-700 mr-2">TDD</span>
              <span class="inline-block bg-gray-200 rounded-full px-3 py-1 my-2 text-sm font-semibold text-gray-700 mr-2">PHPUnit</span>
              <span class="inline-block bg-gray-200 rounded-full px-3 py-1 my-2 text-sm font-semibold text-gray-700">Mocha & Chai</span>
            </div>
          </li>
        </ul>
      </div> <!-- end projects -->
    </div>

  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Ron Mercado'
  }
}
</script>

