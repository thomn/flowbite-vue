<template>
  <div class="vp-raw">
    <flowbite-themable theme="blue">
      <fwb-toast
        alignment="start"
        closable
      >
        <template #icon>
          <svg
            aria-hidden="true"
            class="size-5"
            fill="#ffff"
            viewBox="0 0 20 20"
            xmlns="http://www.w3.org/2000/svg"
          ><path
            clip-rule="evenodd"
            d="M4 2a1 1 0 011 1v2.101a7.002 7.002 0 0111.601 2.566 1 1 0 11-1.885.666A5.002 5.002 0 005.999 7H9a1 1 0 010 2H4a1 1 0 01-1-1V3a1 1 0 011-1zm.008 9.057a1 1 0 011.276.61A5.002 5.002 0 0014.001 13H11a1 1 0 110-2h5a1 1 0 011 1v5a1 1 0 11-2 0v-2.101a7.002 7.002 0 01-11.601-2.566 1 1 0 01.61-1.276z"
            fill-rule="evenodd"
          /></svg>
        </template>
        <span class="mb-1 text-sm font-semibold text-gray-900 dark:text-white">Update available</span>
        <div class="mb-2 text-sm font-normal">
          A new software version is available for download.
        </div>
        <div class="grid grid-cols-2 gap-2">
          <fwb-button size="xs">
            Update
          </fwb-button>
          <fwb-button
            size="xs"
            color="alternative"
          >
            Not now
          </fwb-button>
        </div>
      </fwb-toast>
    </flowbite-themable>
  </div>
</template>

<script lang="ts" setup>
import { FlowbiteThemable, FwbButton, FwbToast } from '../../../../src/index'
</script>
