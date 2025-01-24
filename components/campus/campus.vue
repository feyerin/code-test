<template>
    <div class="container">
        <div class="title">
            Rekomendasi Kampus
        </div>
        <div class="subtitle">
            Memberikan sistim pelayanan untuk para calon mahasiswa Jawa Barat dan Banten
        </div>
        <div class="card-grid">
            <div class="card">
                <img alt="Image of a historical building carved into a cliff" height="200" src="https://storage.googleapis.com/a1aa/image/iMfS7ZRpSSyhTyhgdZCZKLOmM3SBlzxHMleTUGBdilNjfWQoA.jpg" width="300"/>
                <div class="card-content">
                    <img alt="University logo" height="50" src="https://storage.googleapis.com/a1aa/image/DBBLOdSEEv54FNEW6f3kEoeAqs19eEMB7fWrrjAmvOaIebBhC.jpg" width="50"/>
                    <h3>
                    Universitas Muhammadiyah Malang
                    </h3>
                    <div class="location">
                    <i class="fas fa-map-marker-alt">
                    </i>
                    Jakarta Selatan, DKI Jakarta
                    </div>
                    <div class="type" style="color: #F4933A;">
                    - Swasta
                    </div>
                    <div class="tag">
                        Uang masuk mulai dari
                    </div>
                    <div class="price">
                        Rp 350.000
                    </div>
                    <a class="button" href="#">
                    Pendaftaran Online
                    </a>
                </div>
            </div>
        </div>
        <div class="load-button">
            <div class="line"></div>
                <div class="button-container">
                    <a href="#" class="button">Kampus Lainnya (+32)</a>
                </div>
            <div class="line"></div>
        </div>

    </div>
</template>
  
  <script>
  export default {
    // Konten logika layout
  }
  </script>
  
  <style lang="scss">
  @use "~/components/campus/campus.scss";
  </style>