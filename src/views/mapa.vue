<template>
  <div>
    <h1>Mapa</h1>
    <div>
      <img class="mapa" src="../assets/Mapa.jpeg" alt="mapafoto" />
      <img class="indicaciones" src="../assets/Indicaciones.jpeg" alt="ruta" />
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      baseUrl: import.meta.env.BASE_URL,
    };
  },
};
</script>

<style scoped>

img {
  width: 50%;
  height: auto;
  border-radius: 10px;
}

h1 {
  font-family: 'Cormorant Garamond', serif;
  color: rgb(128, 86, 36);
  font-size: 30px;
  text-align: center;
}
</style>

