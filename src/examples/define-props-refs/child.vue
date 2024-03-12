<script setup lang="ts">
import { withDefaults } from 'unplugin-vue-macros/macros' with { type: 'macro' }
import { Assert } from '../../assert'

const { foo } = withDefaults(
  definePropsRefs<{
    foo?: string[]
  }>(),
  { foo: () => ['foobaz'] },
)
</script>

<template>
  
  <Assert :l="foo" :r="['foobaz']" />
</template>
