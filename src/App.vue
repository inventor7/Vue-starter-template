<template>
  <RouterView :dir="$i18n.locale === 'ar' ? 'rtl' : 'ltr'" />
</template>

<script setup>
import { RouterLink, RouterView } from 'vue-router'

</script>

