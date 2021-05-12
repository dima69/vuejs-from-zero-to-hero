<template>
  <div>
    {{animationType}}
      <img
        @click="onClick()"
        class="inline-block ease duration-400 w-10 h-10"
        alt="Vue logo"
        src="../assets/logo.png"
        :class="animationType"
      />
  </div>
</template>

<script>
export default {
  name: "VueLogo",
  props: {
    animationType: {
      type: String,
    },
  },
  methods: {
    onClick() {
      console.log('clickclick');
    },
  }
};
</script>