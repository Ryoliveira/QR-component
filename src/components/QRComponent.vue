<script setup lang="ts">
const frontendMentorLink: string = "https://www.frontendmentor.io/solutions/qr-component-using-padding-and-border-radius-with-a-bit-of-font-css-IrBrFHDvWs";
const githubLink: string = "https://github.com/Ryoliveira";
</script>

<template>
  <!-- main container-->
  <main>
    <section class="main-container">
      <!-- QR Code -->
      <img class="qr-image" src="../assets/image-qr-code.png" alt="qr code to frontendmentor.io" />

      <!-- description text (bold)-->
      <h2 class="description">Improve your front-end skills by building projects</h2>

      <!-- direction text -->
      <p class="directions">Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
    </section>
  </main>

  <footer>Frontend Mentor challenge
     <a :href="frontendMentorLink" aria-label="frontend Mentor Solution" target="_blank">QR Component</a>. 
     Coded by <a :href="githubLink" aria-label="github" target="_blank">Ryan Oliveira</a>
    </footer>
</template>

<style src="../style/scss/qrcomponent.scss" scoped />
