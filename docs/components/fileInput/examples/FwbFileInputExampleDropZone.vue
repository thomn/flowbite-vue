<template>
  <div class="vp-raw">
    <fwb-file-input
      v-model="file"
      dropzone
    />
  </div>
</template>

<script lang="ts" setup>
import { ref } from 'vue'

import { FwbFileInput } from '../../../../src/index'

const file = ref(null)
</script>
