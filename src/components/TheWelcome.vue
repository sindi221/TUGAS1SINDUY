<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>PENDIDIKAN</template>

    Saat ini saya kuliah di salah satu Kampus swasta di Riau yaitu
    <a href="https://uir.ac.id/" target="_blank" rel="noopener">Universitas Islam Riau</a>
    .
    Sebelumnya saya bersekolah di SMA NEGERI
    <a href="https://sekolah.data.kemdikbud.go.id/index.php/chome/profil/ED40A16D-FECF-4B27-9414-7CB5BE597DA5" target="_blank" rel="noopener">SMA NEGERI 1 TAPUNG HILIR </a>
  </WelcomeItem>

  

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Tempat, Tanggal Lahir</template>

    Saya Lahir di DESA <a href="https://id.wikipedia.org/wiki/Riau#Referensi" target="_blank"
      rel="noopener">KOTA GARO </a>
    yaitu
    di KABUPATEN  <a href="https://id.wikipedia.org/wiki/Kota_Pekanbaru" target="_blank"
      rel="noopener">KAMPAR</a>.pada tanggal
    01 Desember 2003

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Jurusan</template>

    Prodi atau Jurusan Kuliah
    Saya mengambil Program studi Teknik Informatika atau biasa disebut TI
    , sekarang saya berada di semester 4 dan berada di kelas yaitu
    <a href="" target="_blank" rel="noopener">4B</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Hobi</template>

    saya memiliki hobi sebagai berikut : <br />
    1.
    <a href="https://www.dicoding.com/blog/apa-itu-coding/" target="_blank" rel="noopener">NGODING</a><br />
    2. <a href="https://id.m.wikipedia.org/wiki/Bulu_tangkis" target="_blank"
      rel="noopener">DUNIA PERMOBILAN</a> <br />
    3. <a href="https://www.gramedia.com/literasi/olahraga-renang/" target="_blank"
      rel="noopener">BERENANG</a> <br />
    4. <a href="https://www.youtube.com/watch?v=10pvNtNoQs8&pp=ygUfYmVsYWphciBtZWxlcGFza2FuIGRpcmlueWEgcmVmZg%3D%3D"
      target="_blank" rel="noopener">JOGING</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Social Media</template>

    Saya suka sosial media akun ini di buat untuk mengabadikan foto yang menurut saya cantik selain itu juga untuk memposting tugas  .<br />
    Instagram = @<a href="https://www.instagram.com/mhd_farhan_/" target="_blank" rel="noopener">sndi_maharani</a> <br />
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>kontak</template>

    no hp :
    <a href="" target="_blank" rel="noopener">0823-4984-6795</a>
    <br>
    email :
    <a href="" target="_blank" rel="noopener">sindiimaharanii@gmail.com</a>
  </WelcomeItem>
</template>