<template>
  <button
    class="btn"
    :type="props.type"
    :disabled="props.disabled"
    @click="props.onClick"
  >
    <slot></slot>
  </button>
</template>

<script lang="ts" setup>
const props = defineProps<{
  type?: "button" | "reset" | "submit" | undefined;
  disabled?: boolean;
  onClick?: (event: MouseEvent) => void;
}>();
</script>
