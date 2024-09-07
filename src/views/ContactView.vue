<template>
  <div class="about">
    <h1 class=" d-flex justify-content-center mt-5">Contacto</h1>
    <div class="d-flex justify-content-center">
  <button @click="VolverAlInicio" class="btn btn-info mb-4">Ir a Inicio</button>
</div>
  </div>
</template>

<script>
export default {
  methods: {
    VolverAlInicio() {
      this.$router.push({ name: 'inicio' })
    }
  }
}
</script>
