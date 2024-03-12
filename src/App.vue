<script setup lang="ts">

import DefinePropsRefs from './examples/define-props-refs/index.vue'

</script>

<template>
  <div grid="~ cols-3 gap2">

    <fieldset>
      <legend>definePropsRefs</legend>
      <DefinePropsRefs />
    </fieldset>

  </div>
</template>

<style>
legend {
  font-family: monospace;
  font-size: 16px;
  font-weight: bold;
}

.ok {
  color: green;
}

.fail {
  font-weight: bold;
  color: red;
}

.ok,
.fail {
  padding: 10px;
}
</style>
