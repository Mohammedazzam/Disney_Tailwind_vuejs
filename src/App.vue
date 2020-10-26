<template>
 <div id="app" class="flex bg-gray-900 text-white min-h-screen">
   <div class="nav w-24 fixed bg-blue-500 min-h-screen flex justify-center items-center">
     <ul>
       <li><a href="#">MOHA</a></li>
     </ul>
   </div>
   <div class="w-full ml-24">
     <router-view/>
   </div>
 </div>
</template>



<style src="./css/main.css">
