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
    <template #heading>About</template>
    my name is Zakiy, i am a student of
     <a target="_blank" href=":/https/smktarunabhakti.net/">SMK Taruna Bhakti,
</a>
   <br> who is interested in IT fields such as design and programming. <br>

    To improve his abilities, i continues to develop his knowledge and <br> skills for further work experience and make a good impact on his <br> career.Currently, he is successfully learning HTML, CSS
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Portofolio</template>

  Team Project (Figma & Web (HTML & CSS) ) <br>
  Implementation Figma to Bootstrap <br>
  Simple Landing Page Bootstrap <br>

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Education</template>

   2020-2023 <br>
   Taruna bhaktiVocational High school <br>
   Majored in Software Engineering / RPL <br>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Languages</template>

    INDONESIA <br>
    INGGRIS <br>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Contact</template>

    <a target="_blank" href="https://vuejs.org/sponsor/">Depok, Indonesia
</a>. <br>
    
    <a target="_blank" href="https://vuejs.org/sponsor/">0896-5439-4698
</a>. <br>

 <a target="_blank" href="https://mail.google.com/mail/u/0/#inbox">zakiyburhan6@gmail.com
</a>. <br>

 <a target="_blank" href="https://github.com/ZakiyBurhan/ZakiyBurhan/">https://github.com/
</a>.
  </WelcomeItem>
</template>
