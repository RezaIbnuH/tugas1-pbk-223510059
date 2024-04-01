<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Tentang Saya</template>
    Nama lengkap saya Reza Ibnu Hanifa, biasa dipanggil Reza. Saya berasal dari Pekanbaru, Riau dan saat ini saya sedang menuntut ilmu di Universitas Islam Riau,
    Jurusan Teknik Informatika. 
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Riwayat Pendidikan</template>
    <ul>
      <li>SDN 33 Pekanbaru (6/6)</li>
      <li>MTs Hasanah Pekanbaru (3/3)</li>
      <li>MA Hasanah Pekanbaru (3/3)</li>
      <li>Universitas Islam Riau (Semester 4 <i>Saat Ini</i>)</li>
    </ul>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Keahlian</template>
    <ul>
      <li>Desain Grafis</li>
      <li>Basis Data</li>
      <li>Pemrograman</li>
      <li>Desain Web</li>
    </ul>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Social Media</template>
    <p class="txt-mercury">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512" width="2em" height="2em" fill="currentColor">
        <path d="M224.1 141c-63.6 0-114.9 51.3-114.9 114.9s51.3 114.9 114.9 114.9S339 319.5 339 255.9 287.7 141 224.1 141zm0 189.6c-41.1 0-74.7-33.5-74.7-74.7s33.5-74.7 74.7-74.7 74.7 33.5 74.7 74.7-33.6 74.7-74.7 74.7zm146.4-194.3c0 14.9-12 26.8-26.8 26.8-14.9 0-26.8-12-26.8-26.8s12-26.8 26.8-26.8 26.8 12 26.8 26.8zm76.1 27.2c-1.7-35.9-9.9-67.7-36.2-93.9s-58-34.5-93.9-36.2c-37.5-1.8-149.9-1.8-187.4 0-35.9 1.7-67.7 9.9-93.9 36.2s-34.5 58-36.2 93.9c-1.8 37.5-1.8 149.9 0 187.4 1.7 35.9 9.9 67.7 36.2 93.9s58 34.5 93.9 36.2c37.5 1.8 149.9 1.8 187.4 0 35.9-1.7 67.7-9.9 93.9-36.2s34.5-58 36.2-93.9c1.8-37.5 1.8-149.9 0-187.4zM398.8 388c-7.8 19.6-22.9 34.7-42.6 42.6-29.5 11.8-99.5 9-132.1 9s-102.7 2.8-132.1-9c-19.6-7.8-34.7-22.9-42.6-42.6-11.8-29.5-9-99.5-9-132.1s-2.8-102.7 9-132.1c7.8-19.6 22.9-34.7 42.6-42.6 29.5-11.8 99.5-9 132.1-9s102.7-2.8 132.1 9c19.6 7.8 34.7 22.9 42.6 42.6 11.8 29.5 9 99.5 9 132.1s2.8 102.7-9 132.1z"/>
      </svg> Instagram
      <a href="https://www.instagram.com/r_y_e_z_a/">@r_y_e_z_a</a>
    </p>
    <p class="txt-mercury">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 320 512" width="2em" height="2em" fill="currentColor">
        <path d="M279.14 288l14.22-92.66h-88.91V142.4c0-25.35 12.42-50.06 52.24-50.06h40.42V6.26S260.43 0 225.36 0c-73.22 0-121.08 44.38-121.08 124.72v70.62H22.89V288h81.39v224h100.17V288z"/>
      </svg> Facebook
      <a href="https://www.facebook.com/ibnu.hanifa.969">Reza Ibnu</a>
    </p>
  </WelcomeItem>
</template>
