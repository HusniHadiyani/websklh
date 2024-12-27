<template>
  <div class="container py-5">
    <h1 class="text-center fw-bold mb-4"> PPLG </h1>
    <p class="text-center mt-4 description">Pengembangan Perangkat Lunak dan Game yang sebelumnya bernama
      Rekayasa Perangkat Lunak (RPL) merupakan salah satu program keahlian di bidang pemrograman yang juga
      menjadi unggulan di SMK Negeri 4 Tasikmalaya </p>
    <div class="image-container text-center">
      <img src="/img/pplg.jpg" alt="pplg" class="img-fluid rounded shadow" />
    </div>
  </div>
</template>

<script>
export default {
  name: 'pplg',
};
</script>

<style scoped>
.container {
  max-width: 800px;
  margin: 0 auto;
}

h1 {
  font-size: 2.5rem;
  color: #333;
}

.image-container {
  margin-top: 2rem;
}

img {
  max-width: 100%;
  height: auto;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease-in-out;
}

img:hover {
  transform: scale(1.05);
}
</style>