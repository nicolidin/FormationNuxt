<template>
  qgd
  <MarkdownText content-md="ddqdld" />
</template>

<script setup lang="ts">

import {MarkdownText} from "vue3-vite-vuetify-lib-starter-kit";

const { t, locale } = useI18n();

import { ref } from "vue";
const val = ref(null);

const config = useRuntimeConfig();


onMounted(() => {
});
</script>

<style scoped lang="scss"></style>
