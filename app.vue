<template>
  <div>
    <NuxtPage />
  </div>
</template>
<script setup>
onMounted(() => {
  const bodyHtml = document.querySelector('body')
  bodyHtml.setAttribute('data-layout', 'detached');
  bodyHtml.setAttribute('detached', 'colored');
})
</script>