<script setup lang="ts">
import { useRuntimeConfig } from '#imports'

const config = useRuntimeConfig()
</script>

<template>
  <div>
    config: {{ config }}
  </div>
</template>
