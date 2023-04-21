<script lang="ts">
import Modal from '../components/Modal.vue'
export default {
  components: {
    Modal
  },
  
  data: () => (
    {
      showModal: false
    }
  )
}
</script>

<template>
  <div class="modal-wrapper">
    <button id="show-modal" @click="showModal = true">
      open
    </button>
    <Teleport to="body">
      <Modal :show="showModal" @close="showModal = false">
        <template #header>
          My modal
        </template>
      </Modal>
    </Teleport>
  </div>
</template>
