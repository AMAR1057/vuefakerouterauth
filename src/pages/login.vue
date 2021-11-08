<script setup>
</script>



<template>
<div 
class="flex flex-col items-center space-y-12 justify-center min-h-screen-nonav">
 
<div
 class="flex items-center justify-center rounded-lg shadow-2xl bg-gray-200">

  <img class="h-64" src="../assets/bglogin.png  " alt="login BG">

<form class="flex flec-col space-y-4 p-4">

  <input 
  type="text"
   class = "p-2 rounded-lg border-2"
    placeholder="Username"  />

  <input type ="password"
   class=" p-2 rounded-lg border-2" 
   placeholder="Password" /> 

  <button type="submit"
   class="text-pink-600 bg-pink-200 py-2 rounded-lg">
   Login
   </button>

  
</form>
</div>

  </div>



</template>