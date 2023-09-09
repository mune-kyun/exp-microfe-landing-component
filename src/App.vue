<template>
  <div
    style="height: 100vh"
    class="w-full flex flex-col justify-center items-center bg-[#add8e6] p-4 relative"
  >
    <div
      class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2 bg-transparent z-50"
    >
      <div
        class="bg-slate-800 bg-opacity-80 p-4 rounded-lg min-w-[500px] flex flex-col items-center gap-2"
      >
        <h1 class="text-white text-5xl font-bold text-center">HoloWaifu</h1>
        <enter-button />
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
import EnterButton from "./components/EnterButton.vue";
export default {
  components: { EnterButton },
  name: "App",
};
</script>
