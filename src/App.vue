<script setup>
//import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <section class="">
   <div class="header py-4">
     <div class="flex flex-col md:flex-row items-center text-white justify-center pb-2">

      <div class="md:p-10">
      <h1 class="text-4xl font-bold">Go! with <i>KZ Edu</i> </h1>
      <h2 class="text-4xl pb-4">Study anywhere - anytime</h2>
      <p>Embrace the power of knowledge through interactive lessons. </p>
      <p>Make your learning an inspiring journey of discovery and growth.</p>
        <div class="flex items-center pt-4"> 
        <button class="px-4 mr-2 py-2 bg-gray-700 text-white rounded hover:bg-gray-500 rounded-full">App store</button> 
        <button class="px-4 ml-2 py-2 bg-gray-700 text-white rounded hover:bg-gray-500 rounded-full">Play store</button> 
        </div>
      </div>

       <div>
        <img src="/src/assets/home.png" alt="Image" class="img-size">
      </div>
    </div>

  </div>

  <!-- features part -->

  <div class="flex flex-col md:flex-row py-6 items-center justify-center bg-orange-50">

    <div class="aspect-w-16 aspect-h-9">
      <img src="/src/assets/features.svg" class="pt-6" alt="">
    </div>

    <div>
    
   <div class="p-4 md:p-10">
  <h1 class="text-3xl md:text-4xl text-black font-bold mb-4 fancy-underline">
    Features
  </h1>

    <div class="text-2xl pb-3 text-gray-500">
  
      <h3>Better Course Management System</h3>
      <h3>Discussion Forums</h3>
      <h3>Assessment and Grading</h3>
      <h3>Personalized Learning Paths</h3>
      <h3>Progress Tracking System</h3>
      <h3>Offline Mode</h3>
      <h3>Multilingual Support</h3>
      <h3>Accessibility Features</h3>
      <h3>Social Sharing</h3>
    </div>

  </div>

  </div>

  </div>

  <!-- pricing -->

  <div class="text-center mt-8"><h1 class="text-3xl md:text-4xl text-black font-bold mb-4">Package plan</h1>
  <p class="text-xl text-slate-600">We have the perfect package for you</p>
  </div>
  <div class="grid grid-cols-1 gap-4 mx-4 my-10 sm:grid-cols-2 lg:grid-cols-4">
        
    <div class="max-w-sm mx-auto bg-green-100 shadow-2xl rounded-lg overflow-hidden text-center">
    <div class="px-10 py-8">
      <h2 class="text-3xl font-bold mb-4 text-black">Basic</h2>
      <p class="text-gray-500 leading-relaxed mb-8">One user</p>
      <p class="text-gray-500 leading-relaxed mb-8">Multiple Access</p>
      <p class="text-gray-500 leading-relaxed mb-8">SMS Support</p>
      <p class="text-gray-500 leading-relaxed mb-8">24/7 Online Support</p>
      <div class="flex items-center justify-between">
        <span class="text-5xl font-bold text-black">$9.99</span>
        <span class="text-sm text-gray-500">/ month</span>
      </div>
      <button class="mt-8 bg-gradient-to-br from-pink-500 to-red-500 hover:from-pink-600 hover:to-red-600 text-white font-bold py-3 px-6 rounded-lg shadow-md">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 inline-block mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"/>
        </svg>
        Choose Plan
      </button>
    </div>
  </div>


  <div class="max-w-sm mx-auto bg-gray-800 border border-gray-700 shadow-lg rounded-lg overflow-hidden text-center">
    <div class="px-10 py-8">
      <h2 class="text-3xl font-bold mb-4 text-white">Standard</h2>
      <p class="text-gray-400 leading-relaxed mb-8">Fiver users</p>
      <p class="text-gray-400 leading-relaxed mb-8">Multiple Access</p>
      <p class="text-gray-400 leading-relaxed mb-8">SMS Support</p>
      <p class="text-gray-400 leading-relaxed mb-8">24/7 Online Support</p>
      <div class="flex items-center justify-between">
        <span class="text-5xl font-bold text-white">$19.99</span>
        <span class="text-sm text-white">/ month</span>
      </div>
      <button class="mt-8 bg-gradient-to-br from-pink-500 to-red-500 hover:from-pink-600 hover:to-red-600 text-white font-bold py-3 px-6 rounded-lg shadow-md">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 inline-block mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"/>
        </svg>
        Choose Plan
      </button>
    </div>
  </div>


  <div class="max-w-sm mx-auto bg-green-100 shadow-2xl rounded-lg overflow-hidden text-center">
    <div class="px-10 py-8">
      <h2 class="text-3xl font-bold mb-4 text-black">Premium</h2>
      <p class="text-gray-500 leading-relaxed mb-8">One user</p>
      <p class="text-gray-500 leading-relaxed mb-8">Multiple Access</p>
      <p class="text-gray-500 leading-relaxed mb-8">SMS Support</p>
      <p class="text-gray-500 leading-relaxed mb-8">24/7 Online Support</p>
      <div class="flex items-center justify-between">
        <span class="text-5xl font-bold text-black">$29.99</span>
        <span class="text-sm text-gray-500">/ month</span>
      </div>
      <button class="mt-8 bg-gradient-to-br from-pink-500 to-red-500 hover:from-pink-600 hover:to-red-600 text-white font-bold py-3 px-6 rounded-lg shadow-md">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 inline-block mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"/>
        </svg>
        Choose Plan
      </button>
    </div>
  </div>

  <div class="max-w-sm mx-auto bg-green-100 shadow-2xl rounded-lg overflow-hidden text-center">
    <div class="px-10 py-8">
      <h2 class="text-3xl font-bold mb-4 text-black">Enterprise</h2>
      <p class="text-gray-500 leading-relaxed mb-8">One user</p>
      <p class="text-gray-500 leading-relaxed mb-8">Multiple Access</p>
      <p class="text-gray-500 leading-relaxed mb-8">SMS Support</p>
      <p class="text-gray-500 leading-relaxed mb-8">24/7 Online Support</p>
      <div class="flex items-center justify-between">
        <span class="text-5xl font-bold text-black">$39.99</span>
        <span class="text-sm text-gray-500">/ month</span>
      </div>
      <button class="mt-8 bg-gradient-to-br from-pink-500 to-red-500 hover:from-pink-600 hover:to-red-600 text-white font-bold py-3 px-6 rounded-lg shadow-md">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 inline-block mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"/>
        </svg>
        Choose Plan
      </button>
    </div>
  </div>

</div>


<!-- special facts -->

  <div class="flex flex-col bg-gray-500 items-center text-white py-8">
  <div class="text-center mb-4">
    <h1 class="text-4xl font-bold mb-4">Special facts</h1>
   
    <ul class="list-none p-0 m-0">
    <li class=" py-2">
   <p class="text-lg text-white mt-4 md:mt-0">20K download in 4 weaks</p>
    </li>
    <li class=" py-2">
   <p class="text-lg text-white mt-4 md:mt-0">10K purchased in 5 weaks</p>
   
    </li>
    <li class=" py-2">
   <p class="text-lg text-white mt-4 md:mt-0">10k 5 star reveiw and 20k 4 star review</p>
    </li>
    <li class=" py-2">
   <p class="text-lg text-white mt-4 md:mt-0">3 major updates in 2 months and new updates this year</p>
  </li>
   
</ul>

  </div>


  <div class="mb-2">
    <img src="/src/assets/footer.png" alt="">
  </div>
  
</div>

<!-- footer -->
<div class="flex flex-col bg-slate-800 items-center text-white py-8">
  <img src="/src/assets/logo.png" class="logo-size m-0" alt="">
  <h4 class="text-sm text-gray-200">&copy; 2023 <strong><i>  KZ Edu</i></strong>  . All rights reserved.</h4>
</div>

</section>

</template>

<style scoped>
.header {
  background-image: linear-gradient(to left, #ee4444, #f87952);
}

.logo-size{
  height: 20vh;
  width: 20vh;
}
.img-size {
  width: 3in;
  height: 3.5in;
  max-width: 100%;
  max-height: 100%;
  object-fit: contain;
}

</style>
