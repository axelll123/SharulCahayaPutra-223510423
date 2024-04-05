<script setup lang="ts">
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
    <template #heading>Tentang</template>
    Perkenalkan saya Sharul Cahaya Putra atau biasa dipanggil Sarul, Saya Alumni SMA Negeri 5 Pekanbaru.
    Saat ini saya tinggal di Jalan Nenas,No.15 A Pekanbaru 
    Dan saat ini saya sedang Berkuliah di Universitas Islam Riau prodi Teknik Informatika (S1)
</WelcomeItem>
  <hr />
  
  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Hobi</template>
    Saya mengisi waktu luang saya dengan kegiatan bermanfaat sekaligus menyalurkan hobi saya :
    <ul>
      <li>Basket</li>
      <li>futsal</li>
      <li>Renang</li>
    </ul>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Pengalaman</template>
    Saya memiliki pengalaman berdasarkan beberapa hobi saya:
    <ul>
    <li>Turnament Basket</li>
      <li>Turnament Futsal</li>
      <li>Anngota Osis</li>
      <li>mengikuti seminar Internet Of Think</li>
</ul>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Skill</template>
    <li>Jaringan</li>
    <li>Mikrotik</li>
    <li>Setting IP</li>
    <li>HTML</li>
    <li>C++</li>
      
  </WelcomeItem>
  <hr/>
  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Contact</template>
Kalian dapat menghubungi saya melalui : <br/>
 Instagram : <a href="https://www.instagram.com/sarulchyaptra" target="_blank">sarulchyaptra</a><br/>
 Email : sharulcahyaputra@gmail.com <br/>
 HP : +62 878-4760-6591
  </WelcomeItem>
</template>