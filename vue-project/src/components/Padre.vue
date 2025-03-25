<script>
import Editor from './Editor.vue'
export default {
  data() {
    return {
      titulo: '',
    }
  },

  components: {
    'componente-editor': Editor,
  },
}
</script>

<template>
  <componente-editor v-bind:textoAEditar="titulo" />
</template>
