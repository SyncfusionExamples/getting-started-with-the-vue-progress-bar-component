<script setup>
import { ProgressBarComponent as EjsProgressbar }
 from '@syncfusion/ej2-vue-progressbar';
</script>

<template>
<div class="container">
  <ejs-progressbar height="160" width="160" isStriped="false"
  minimum="1" maximum="50" value="25" trackThickness="12"
  progressThickness="12" trackColor="#F8C7D8" progressColor="#E3165B"
  type="Circular">
  </ejs-progressbar>
</div>
</template>

<style scoped>
.container {
  padding-bottom: 160px;
}
</style>
