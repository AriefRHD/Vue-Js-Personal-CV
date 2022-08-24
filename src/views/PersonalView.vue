<script setup>
// import TheWelcome from '@/components/TheWelcome.vue'
</script>

<template>
  <main>

    <div class="containernya">
    <h2 class="buat-tengah">PROFIL SAYA</h2>
    <div class="buat_df">
    <div class="inian">
      
      
      <br>
      <img alt="foto" class="foto_cv" src="@/assets/foto_cv.jpeg" width="300" height="385" />
    </div>
    <br>
    <div class="container">
        <br>
        <h4>Tentang Saya</h4>
        <p>Saya Arief Rahman Hidayat siswa SMK Taruna Bhakti
            berumur 17 tahun dengan jurusan Rekayasa Perangkat
            Lunak, Berpengalaman mengembangkan website
            menggunakan HTML, CSS, Bootstrap, Javascript dasar. <br>
            Selain itu saya juga memiliki pengalaman
            menggunakan Laravel, dan MYSQL.</p>
        
        <h4>Role Pekerjaan</h4>
        <p>Front End</p>

        <h4>Pendidikan</h4>
        <p>SMK TARUNA BHAKTI <br> 2020 - 2023 Rekayasa Perangkat Lunak</p>
        <h4>Alamat</h4>
        <p>Perumahan Damai Indah Residence Blok B 3A</p>
        <h4>Email</h4>
        <p>Ariefrhd30@gmail.com</p>
        <h4>No HP</h4>
        <p>+62 895378939837</p>
        <!-- <h1>huhuhaha</h1> -->
        
            
    </div>
    </div>
    </div>




    <!-- <TheWelcome /> -->
  </main>
</template>
<style>
p{
  font-weight: 500;
  color: rgb(99, 99, 99);
}

.buat-tengah{
  text-align: center;
}

.buat_df{
  display: flex;
  
}

.foto_cv{
  border-radius: 20px;
}

.containernya{
  box-shadow: rgba(0, 0, 0, 0.19) 0px 10px 20px, rgba(0, 0, 0, 0.23) 0px 6px 6px;
  border-radius: 20px;
  padding: 2rem;
  padding-left: 5rem;
}

.container{
  padding-left: 2rem;
}


</style>
