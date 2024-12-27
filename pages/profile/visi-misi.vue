<template>
  <div class="container py-5">
    <h1 class="text-center fw-bold mb-3">Visi Misi</h1>
    <div class="content mt-4">
      <h2 class="fw-bold">Visi</h2>
      <p>Berlandaskan Iman dan Taqwa, SMK Negeri 4 Tasikmalaya Berprestasi, Terampil dan Mandiri.</p>
      <h2 class="fw-bold mt-4">Misi</h2>
      <ol>
        <li>Meningkatkan kedisiplinan peserta didik.</li>
        <li>Meningkatkan pemahaman, penghayatan dan pengalaman keagamaan bagi peserta didik di sekolah.</li>
        <li>Mewujudkan nilai-nilai solidaritas bagi kehidupan sekolah.</li>
        <li>Memberdayakan pendidik dan tenaga kependidikan yang mampu dan Tangguh.</li>
        <li>Mewujudkan sekolah inovatif dalam pembelajaran.</li>
        <li>Meningkatkan tanggung jawab, percaya diri dan semangat untuk berkompetensi pada peserta didik.</li>
        <li>Memenuhi fasilitas sekolah yang relevan mutakhir dan berwawasan kedepan.</li>
        <li>Meningkatkan Pendidikan karakter peserta didik.</li>
        <li>Mewujudkan sekolah sehat.</li>
        <li>Mewujudkan pembiayaan Pendidikan yang memadai wajar dan adil.</li>
      </ol>
    </div>
  </div>
</template>

<script>
export default {
  name: 'VisiMisi',
};
</script>

<style scoped>
.container {
  max-width: 800px;
  margin: 0 auto;
}

h1 {
  font-size: 2.5rem;
}

h2 {
  font-size: 1.5rem;
  margin-bottom: 0.5rem;
  color: #333;
}

.text-muted {
  font-size: 0.9rem;
}

ol {
  padding-left: 1.5rem;
  line-height: 1.8;
}

ol li {
  margin-bottom: 0.5rem;
}
</style>