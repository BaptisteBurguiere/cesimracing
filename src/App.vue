<template>
  <header class="flex flex-row items-center mt-4 w-screen">
    <nav class="navbar flex flex-row w-full items-center justify-between">
      <div class="w-[0%] xl:w-[20%] h-full "></div>
      <div class="w-full h-full flex items-center justify-center ">
        <router-link to="/home" class="text-[#D3D3D3] font-barlowcondensed text-3xl xl:text-4xl ">ACCUEIL</router-link>
        <router-link to="/home" class="text-[#D3D3D3] font-barlowcondensed text-3xl xl:text-4xl ml-11 xl:ml-14">PRESENTATION</router-link>
        <router-link to="/home" class="mx-12 xl:mx-16">
          <img src="src\assets\images\Vaillante_logo.svg.png" alt="logo" class="xl:h-20 xl:w-20 h-16 w-16">
        </router-link>
        <router-link to="/home" class="text-[#D3D3D3] font-barlowcondensed text-3xl xl:text-4xl mr-11 xl:mr-14">CHAMPIONNATS</router-link>
        <router-link to="/home" class="text-[#D3D3D3] font-barlowcondensed text-3xl xl:text-4xl">GALERIE</router-link>
      </div>
      <div class="w-[25%] h-full  flex items-center justify-center">
        <router-link to="/home" class="text-white font-barlowcondensed bg-[#B63831] px-4 py-2 xl:px-5 xl:py-3 text-2xl xl:text-3xl rounded-2xl xl:rounded-3xl">REJOIGNEZ-NOUS</router-link>
      </div>
    </nav>
  </header>
</template>

<script>
export default {

}
</script>

<style>

</style>