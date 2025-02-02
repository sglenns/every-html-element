<template>
  <!-- Dialog Element -->
  <Button @click="showModal"> Or click me </Button>
  <dialog class="modal" ref="currentDialog">
    <div class="modal-box">
      <h3 class="text-lg font-bold">Hello!</h3>
      <p class="py-4">Press ESC key or click the button below to close</p>
      <div class="modal-action">
        <form method="dialog" @submit="hideModal">
          <!-- if there is a button in form, it will close the modal -->
          <button class="btn">Close</button>
        </form>
      </div>
    </div>
  </dialog>
</template>

<script setup lang="ts">
const currentDialog = ref();
function showModal() {
  currentDialog.value.showModal();
}
function hideModal() {
  currentDialog.value.close();
}
</script>
