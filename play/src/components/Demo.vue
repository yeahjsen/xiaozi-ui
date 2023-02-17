<template>
  <XZAlert title="hello" closable :model-value="isOpen">
    <template #title> abcde </template>
  </XZAlert>
  <v-icon icon="mdi:mdi-minus" />
</template>

<script setup>
import XZAlert from "@xiaozi-ui/components/alert";
</script>
