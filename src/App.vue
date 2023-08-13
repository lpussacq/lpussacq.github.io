<script setup lang="ts">
import Highlight from "./views/Highlight.vue"
import Content from "@/views/Content.vue"
</script>

<template>
  <div class="container text-bg-light">
    <div class="row">
      <Highlight class="col-3 hightlight"></Highlight>
      <Content class="col-9 body"></Content>
    </div>
  </div>
</template>

