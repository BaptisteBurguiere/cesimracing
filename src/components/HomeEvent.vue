<template>
  <div class="HomeEvent flex justify-center items-center">
    <img class="h-[9.5rem] w-[15.8rem]" src="https://cdn.discordapp.com/attachments/984140745374068857/986521021089726484/Screenshot_wec_lmp1_rebellion_r13_2018_ks_silverstone_14-5-122-21-33-22.jpg" alt="Event image">
    <div class="h-[9.5rem] w-[15.8rem] bg-[#B63831] pl-7 pt-7 ">
      <h2 class="font-barlowsemicondensed text-[#D3D3D3] text-xl">Prochain championnat</h2>
      <h1 class="font-barlowcondensed text-[#D3D3D3] text-4xl">MINI CHAMP</h1>
    </div>
    <div class="h-[7.8rem] w-[15.4rem] bg-[#4d4d4dbb] flex items-center flex-col justify-center graybox">
      <div>
        <h1 class="font-barlowcondensed text-[#EEEEEE] text-3xl">19 COURSES</h1>
        <h2 class="font-barlowsemicondensed text-[#eeeeeee8] text-2xl mt-[-0.4rem]">Endurance</h2>
      </div>
    </div>
    <div class="h-[7.8rem] w-[15.4rem] bg-[#4d4d4dbb] flex items-center flex-col justify-center graybox">
      <div>
        <h1 class="font-barlowcondensed text-[#EEEEEE] text-3xl">38 PARTICIPANTS</h1>
        <h2 class="font-barlowsemicondensed text-[#eeeeeee8] text-2xl mt-[-0.4rem]">Endurance</h2>
      </div>
    </div>
    <div class="h-[7.8rem] w-[15.4rem] bg-[#4d4d4dbb] flex items-center flex-col justify-center graybox">
      <div>
        <h1 class="font-barlowcondensed text-[#EEEEEE] text-3xl">4 CATEGORIES</h1>
        <h2 class="font-barlowsemicondensed text-[#eeeeeee8] text-2xl mt-[-0.4rem]">Endurance</h2>
      </div>
    </div>
  </div>
</template>

<script>
export default {
    name: 'HomeEvent',
}
</script>

<style>
  .graybox{
    box-shadow: inset 0px 4px 4px rgba(0, 0, 0, 0.25);
  }
</style>