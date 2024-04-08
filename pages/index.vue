<template>
  <NuxtLayout>
    <Button @click="setLocale('en')">{{ $t('welcome') }}</Button>
  </NuxtLayout>
</template>

<script setup lang="ts">
import { Button } from "@wingui/vue"
const { locale, setLocale } = useI18n()

definePageMeta({
  layout: 'default'
})
</script>