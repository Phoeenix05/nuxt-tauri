<template>
  <div>
    <NuxtWelcome />
  </div>
</template>

<script lang="ts">
import { invoke } from "@tauri-apps/api/tauri"

invoke("hello", {})
</script>