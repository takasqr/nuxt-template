<template>
  <Button @click="setLocale('en')">{{ $t('welcome') }}</Button>
</template>

<script setup lang="ts">
import { Button } from "@wingui/vue"
const { locale, setLocale } = useI18n()
</script>