<template>
  <div>TEST PREVIEW DEPLOY!</div>
</template>

<script setup>
const { data: news } = await useFetch('/rcms-api/1/news/list');
const { data: ltdNews } = await useFetch('/rcms-api/1/ltd-news/list');
</script>
