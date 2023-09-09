<template>
  <div
    style="height: 100vh"
    class="w-full flex flex-col justify-center items-center bg-[#add8e6] p-4 relative"
  >
    <div
      class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2 bg-transparent z-50"
    >
      <div class="bg-slate-800 bg-opacity-80 p-4 rounded-lg min-w-[500px]">
        <h1 class="text-white text-2xl font-bold text-center">HoloWaifu</h1>
      </div>
    </div>
    <div class="flex gap-3 items-center justify-center">
      <img class="w-1/4 h-fit opacity-70" src="@/assets/korone.gif" />
      <img class="w-1/4 h-fit opacity-70" src="@/assets/miko.gif" />
      <img class="w-1/4 h-fit opacity-70" src="@/assets/suisei.gif" />
    </div>
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style></style>
