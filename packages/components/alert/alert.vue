<template>
  <v-alert v-bind="$attrs">
    <template #append v-if="$slots.append">
      <slot name="append"></slot>
    </template>
    <template #close v-if="$slots.close">
      <slot name="close"></slot>
    </template>
    <template #default v-if="$slots.default">
      <slot></slot>
    </template>
    <template #prepend v-if="$slots.prepend">
      <slot name="prepend"></slot>
    </template>
    <template #text v-if="$slots.text">
      <slot name="text"></slot>
    </template>
    <template #title v-if="$slots.title">
      <slot name="title"></slot>
    </template>
  </v-alert>
</template>
