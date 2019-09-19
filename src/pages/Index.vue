<template>
  <Layout>
    <div class="hero container-inner mx-auto flex flex-col sm:flex-row justify-between py-16">
      <div class="font-bold w-full sm:w-3/5 text-center mx-auto">
        <div class="text-4xl leading-tight">Jacob Carpenter</div>
        <div class="text-3xl text-green-700 leading-tight">Front End Developer specializing in Vue.js, Tailwind &amp; Craft CMS</div>
      </div>
    </div> <!-- end hero -->

    <div class="container-inner mx-auto mb-16">
      <p class="text-lg sm:text-xl">Hi there! I'm Jacob and I like to create web related things. No really, <strong>I love creating stuff for the web</strong>. I am a frontend developer currently working for the fine folks at <a href="https://rockitscienceagency.com">Rockit Science Agency</a>. I build and design modern websites that are highly functional for todays fast paced world. I occasionally design a logo here and there as well. When I'm not doing these things, I'm usually hanging out with my family <strike>enjoying</strike> this lovely humid Louisiana weather. Below are some projects I've done. If you like what you see and want to know what else I'm capable of, shoot me an <a href="mailto:jacob@jacobpaulcarpenter.com">email</a> and I'd be happy to do just that.</p>
    </div>

    <div class="overflow-x-hidden">
      <div class="projects container-inner mx-auto text-xl border-t border-gray-500 py-16 mb-6 relative">
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
      <div class="contact-me bg-background-tertiary pt-16">
        <div class="container-inner mx-auto text-xl pb-4 relative">
          <h2 class="font-bold mb-6" id="contact">Contact me:</h2>

          <div class="absolute right-0 top-0" style="transform: translate(100%) rotate(180deg)">
            <svg width="170px" height="170px"><use xlink:href="#dots-triangle" /></svg>
          </div>

          <p class="mb-12">Looking to launch a new product or business? Need a website built to reflect your business model and inform your customers on what's coming? Lets build something great together. Contact me below and we'll get this thing rolling.</p>

          <div class="text-lg sm:text-lg mb-16">
            <form name="contact" netlify method="POST" class="mb-12">
              <div class="flex flex-wrap mb-6 -mx-4">
                  <div class="w-full md:w-1/2 mb-6 md:mb-0 px-4">
                      <label class="block mb-2 text-copy-primary" for="name">
                          Name
                      </label>

                      <input type="text" name="name" id="name" placeholder="Jon Snow" class="block w-full bg-background-form border border-border-color-primary shadow rounded outline-none focus:border-green-700 mb-2 p-4" required>
                  </div>

                  <div class="w-full px-4 md:w-1/2">
                      <label class="block text-copy-primary mb-2" for="email">
                          Email Address
                      </label>

                      <input type="email" name="email" id="email" placeholder="email@example.com"  class="block w-full bg-background-form border border-border-color-primary shadow rounded outline-none focus:border-green-700 mb-2 p-4" required>
                  </div>
              </div>

              <div class="w-full mb-12">
                  <label class="block text-copy-primary mb-2" for="message">
                      Message
                  </label>

                  <textarea id="message" rows="5" name="message" class="block w-full bg-background-form border border-border-color-primary shadow rounded outline-none appearance-none focus:border-green-700 mb-2 px-4 py-4" placeholder="Enter your message here." required></textarea>
              </div>

              <div class="flex justify-end w-full">
                  <input type="submit" value="Submit" class="block bg-green-700 hover:bg-green-800 text-white text-sm font-semibold tracking-wide uppercase shadow rounded cursor-pointer px-6 py-3">
              </div>
          </form>
          </div>
        </div>
      </div> <!-- end contact-me -->
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

