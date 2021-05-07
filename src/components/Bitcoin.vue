<template>
  <div class="row justify-between">
    <q-parallax
      src="https://image.winudf.com/v2/image/Y29tLnRydWVoZHdhbGxwYXBlcnMuYml0Y29pbndhbGxwYXBlcnNfc2NyZWVuXzNfMTUxMjU2ODY1MV8wMjA/screen-3.jpg?fakeurl=1&type=.jpg"
    >
        <div class="absolute-full blured"></div>
      <div class="absolute-full text-white">
        <h1>Bitcoin</h1>
      </div>
    </q-parallax>
    <div style="height:10000px"></div>
  </div>
</template>

<style lang="scss" scoped>
.blured {
    background: $dark;
    opacity: 0.5;
}
</style>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'Bitcoin',
  props: {},
});
</script>
