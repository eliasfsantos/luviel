<script setup>
import WelcomeItem from './WelcomeItem.vue'
import InstagramIcon from './icons/IconInstagram.vue'
import EmailIcon from './icons/IconEmail.vue'

const openReadmeInEditor = () => fetch('/__open-in-editor?file=README.md')
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <InstagramIcon />
    </template>
    <template #heading>Instagram</template>

    Veja a página do 
    <a href="https://instagram.com/luvielengenharia" target="_blank" rel="noopener">instagram</a>
    da Luviel Engenharia 
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EmailIcon />
    </template>
    <template #heading>Email</template>

    Entre em contato conosco através do nosso
    <a href="mailto:contato@luviel.com.br" target="_blank" rel="noopener">E-mail</a>: 
    <a href="mailto:contato@luviel.com.br" target="_blank" rel="noopener">contato@luviel.com.br</a>

  </WelcomeItem>

</template>
