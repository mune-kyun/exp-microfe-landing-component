<template>
  <button class="text-white text-lg underline font-semibold" @click="goIn">
    ENTER ➔
  </button>
</template>

<script>
export default {
  name: "EnterButton",
  methods: {
    goIn() {
      const event = new CustomEvent("InterComponent", {
        detail: {
          customData: {
            from: "landing-component",
            action: "press-enter",
          },
        },
      });
      dispatchEvent(event);
    },
  },
};
</script>
