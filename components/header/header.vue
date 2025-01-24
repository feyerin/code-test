<template>
    <div id="header" class="header">
        <div class="logo">
          <img src="~/assets/img/logo.png" alt="logo" />
        </div>

        <div class="searchbar">
          <img src="~/assets/icon/search.png" alt="icon" />
          <input type="text" class="search" placeholder="Cari kampus/prodi impian Anda disini...">
          <button class="btn-search">cari</button>
        </div>

        <div class="header-right">
          <button class="btn-register">Daftar</button>
          <button class="btn-login">Login</button>
        </div>
    </div>
</template>
<script>
  export default {
    // Konten logika layout
  }
</script>

<style lang="scss">
@use "~/components/header/header.scss";
</style>