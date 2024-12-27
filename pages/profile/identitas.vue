<template>
  <div class="container py-5">
    <h1 class="text-center mb-3">Identitas Sekolah</h1>
    <div class="text-center mb-4">
      <img src="/img/logo1.png" alt="Logo Sekolah" class="logo-img" />
    </div>
    <table class="table table-bordered table-striped">
      <tbody>
        <tr>
          <td><strong>NPSN</strong></td>
          <td>20224584</td>
        </tr>
        <tr>
          <td><strong>Tanggal SK Pendirian</strong></td>
          <td>26 juli 1955</td>
        </tr>
        <tr>
          <td><strong>Nama Sekolah</strong></td>
          <td>SMK Negeri 4 Tasikmalaya</td>
        </tr>
        <tr>
          <td><strong>Alamat</strong></td>
          <td>Jl. depok</td>
        </tr>
        <tr>
          <td><strong>Kelurahan</strong></td>
          <td>purbaratu</td>
        </tr>
        <tr>
          <td><strong>Kecamatan</strong></td>
          <td>purbartu</td>
        </tr>
        <tr>
          <td><strong>Kota</strong></td>
          <td>Tasikmalaya</td>
        </tr>
        <tr>
          <td><strong>Kode POS</strong></td>
          <td>46196</td>
        </tr>
        <tr>
          <td><strong>Provinsi</strong></td>
          <td>Jawa Barat</td>
        </tr>
        <tr>
          <td><strong>Telepon/Fax</strong></td>
          <td> +62265312059</td>
        </tr>
        <tr>
          <td><strong>Email</strong></td>
          <td>info@smkn4tsm.sch.id</td>
        </tr>
      </tbody>
    </table>
  </div>
</template>

<script>
export default {
  name: 'IdentitasSekolah',
};
</script>

<style scoped>
.container {
  max-width: 800px;
  margin: 0 auto;
}

.logo-img {
  max-width: 150px;
  height: auto;
}

.table td:first-child {
  width: 40%;
  font-weight: bold;
}
</style>