<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container">
      <a class="navbar-brand d-flex align-items-center" href="#">
        <img src="/img/logo.png" alt="Logo" width="40" height="40" class="me-2" />
        SMKN 4 TASIKMALAYA
      </a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
        aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" aria-current="page" href="/">Home</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="profileDropdown" role="button" data-bs-toggle="dropdown"
              aria-expanded="false"> profile </a>
            <ul class="dropdown-menu" aria-labelledby="profileDropdown">
              <li><a class="dropdown-item" href="pages/profile/identitas">Identitas Sekolah</a></li>
              <li><a class="dropdown-item" href="pages/profile/sejarah">Sejarah</a></li>
              <li><a class="dropdown-item" href="pages/profile/visi-misi">Visi & Misi</a></li>
            </ul>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="ekskulDropdown" role="button" data-bs-toggle="dropdown"
              aria-expanded="false"> Ekstrakurikuler </a>
            <ul class="dropdown-menu" aria-labelledby="ekskulDropdown">
              <li><a class="dropdown-item" href="/ekstrakurikuler/osis">Osis</a></li>
              <li><a class="dropdown-item" href="/ekstrakurikuler/voli">Bola Voli</a></li>
              <li><a class="dropdown-item" href="/ekstrakurikuler/pramuka">pramuka</a></li>
            </ul>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="ekskulDropdown" role="button" data-bs-toggle="dropdown"
              aria-expanded="false"> jurusan </a>
            <ul class="dropdown-menu" aria-labelledby="jurusanDropdown">
              <li><a class="dropdown-item" href="/jurusan/tjkt">tjkt</a></li>
              <li><a class="dropdown-item" href="/jurusan/pplg">pplg</a></li>

            </ul>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <hr />
</template>

<script setup></script>

<style scoped>
.navbar-brand {
  font-weight: bold;
}

.navbar-brand img {
  border-radius: 50%;
}
</style>