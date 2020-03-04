<template>
  <span ref="blinkyText"> <slot /></span>
</template>

<script>
export default {
  name: 'blink',
  mounted() {
    setInterval(() => {
      this.$refs.blinkyText.classList.toggle("onoff");
    }, this.interval);
  },
  props: {
    interval: {
      type: Number,
      default: 4000
    }
  }
}
</script>

<style>
.onoff {
  visibility: hidden;
}
</style>
