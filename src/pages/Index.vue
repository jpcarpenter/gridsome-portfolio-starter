<template>
  <Layout>


    <div class="hero container-inner mx-auto flex flex-col sm:flex-row justify-between pt-0 pb-8 md:py-8">
      <div class="font-bold w-full sm:w-3/5 text-center mx-auto">
        <!-- <div class="flex flex-col sm:flex-row justify-center items-center mb-6">
          <div>
              <g-image src="../../static/avatar.jpg" alt="avatar" class="w-32 h-32 rounded-full" />
          </div>
        </div> -->
        <h1 class="text-4xl leading-tight">Jacob Carpenter</h1>
        <h2 class="text-3xl text-green-700 leading-tight">Front End Developer specializing in Craft CMS,  Vue.js &amp; Tailwind.</h2>
      </div>
    </div> <!-- end hero -->

    <div class="container-inner mx-auto mb-16 text-center">
      <p class="text-lg sm:text-xl mb-12">Hi there! I am a front end developer in Baton Rouge, Louisiana currently working for the fine folks at <a target="_blank" href="https://rockitscienceagency.com">Rockit Science Agency</a>. I build and design modern websites that are highly functional for todays digital age.</p>
       <a href="mailto:jacob@jacobpaulcarpenter.com" class="bg-green-700 hover:bg-green-800 py-3 px-4 text-white rounded hover:text-white">Contact me</a>
    </div>

    <div class="overflow-x-hidden">
      <div class="projects container-inner mx-auto text-xl border-t border-gray-500 py-16 relative">
        <h2 class="font-bold mb-6" id="projects">Here are some projects I've worked on:</h2>

        <div class="absolute right-0" style="top: 50px; transform: translate(100%) rotate(180deg)">
          <svg width="170px" height="170px"><use xlink:href="#dots-triangle" /></svg>
        </div>

        <ul class="text-lg sm:text-xl">
          <li class="checkmark mb-6">
            <div>Precision Weld Testing &amp Training</div>
            <div class="text-lg text-gray-600">Website designed and developed for a local industrial education facility. Site built on Craft CMS and UIkit 3. <a href="https://precisionwtt.com" target="_blank">View the Website</a></div>
          </li>
          <li class="checkmark mb-6">
            <div>Hidden Beauty Salon</div>
            <div class="text-lg text-gray-600">Website designed and developed for a local hair salon which alows clients to book appointments online as well as view pricing. Site built on Craft CMS and UIkit 3. Logo and branding done by Jacob Carpenter as well. <a href="https://hiddenbeautyla.com" target="_blank">View the Website</a></div>
          </li>
        </ul>
      </div> <!-- end projects -->
    </div>
    <div class="overflow-x-hidden">
      <div class="contact-me bg-background-tertiary py-16 overflow-hidden">
        <div class="container-inner mx-auto text-xl relative text-center" id="contact">

          <div class="absolute right-0 top-0" style="transform: translate(100%) rotate(180deg)">
            <svg width="170px" height="170px"><use xlink:href="#dots-triangle" /></svg>
          </div>
          <h2 class="text-3xl text-green-700 font-bold leading-tight mb-6">Let's Work Together</h2>
          <p class="mb-12">Looking to launch a new product or business? Need a website built to reflect your business model and inform your customers on what's coming? Lets build something great together. Contact me below and we'll get this thing rolling.</p>
          <a href="mailto:jacob@jacobpaulcarpenter.com" class="bg-green-700 hover:bg-green-800 py-3 px-4 text-white rounded hover:text-white">Contact me</a>
        </div>
      </div>
    </div>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Home'
  }
}
</script>

