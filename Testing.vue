<script setup lang="ts">
import {useCssModule} from "vue";
const $style = useCssModule();
</script>

<template>
  <div :class="$style.container"></div>
</template>

<style module>
.container {

}
</style>