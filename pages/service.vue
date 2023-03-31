<template>
  <div class="bg-white mt-6">
    <h2 class="text-3xl text-indigo-600 font-bold uppercase text-center mb-2">Our Service</h2>

    <div class="container mx-auto py-12 px-4">
      <h1 class="text-3xl font-bold mb-6">Professional Services</h1>
      <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-6">
        <div class="bg-gray-100 rounded-lg shadow-lg p-6">
          <h2 class="text-xl font-semibold mb-4">Mission</h2>
          <p class="text-gray-700 mb-4 text-justify">


            Our mission is to provide clean and safe drinking water to communities in need, improving their health and
            well-being. We source and purify water from rivers or underground sources and distribute it to those who
            need it most.


          </p>

          <a href="#" class="text-blue-600 hover:text-blue-800 font-semibold">Learn more</a>
        </div>
        <div class="bg-gray-100 rounded-lg shadow-lg p-6">
          <h2 class="text-xl font-semibold mb-4 text-justify">Vision</h2>
          <p class="text-gray-700 mb-4">

            Our vision is a world where everyone has access to clean and safe drinking water as a basic human right. We
            aim to eradicate waterborne diseases and enable children to attend school instead of fetching water all day.

          </p>
          <a href="#" class="text-blue-600 hover:text-blue-800 font-semibold">Learn more</a>
        </div>
        <div class="bg-gray-100 rounded-lg shadow-lg p-6">
          <h2 class="text-xl font-semibold mb-4">Values</h2>
          <p class="text-gray-700 mb-4 text-justify">
            At Water4all, We are committed to using sustainable practices in our operations to ensure that our impact
            is long-lasting and positive. We believe in working together with communities, governments, and other organisations to
            achieve our mission.

          
          </p>
          <a href="#" class="text-blue-600 hover:text-blue-800 font-semibold">Learn more</a>
        </div>
      </div>
      <div
        class="bg-hero rounded-lg shadow-lg h-screen flex justify-center items-center overlay mt-6 w-full h-full object-cover opacity-60">
        <div class="flex flex-col justify-center items-center h-full">

        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    // Add any necessary script here
  }
</script>

<style>
  .bg-hero {
    background-image: url("../assets/img/back-image.jpg");
    background-color: #00000081;
    background-size: cover;
  }
</style>