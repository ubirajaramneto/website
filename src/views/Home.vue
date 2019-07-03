<template>
  <div class="container mx-auto flex flex-col items-center mt-20 p-3">
    <img src="@/assets/images/profile-pic-square.jpg" class="h-48 w-48 content-center rounded-full" alt="">
    <div class="text-left mt-4">
    <h1 class="text-center text-xl md:text-4xl text-gray-800 font-mono">Ubirajara Marsicano Neto</h1>
    <h2 class="text-center text-xl md:text-4xl text-gray-800 font-sans font-light">I'm a software engineer and developer</h2>
      <p class="mt-4 font-sans">I have <span class="text-gray-800 font-bold">over 6 years of experience building and designing software applications.</span></p>
      <p class="font-sans">If you would like to get in touch you can send me an e-mail to: <span class="text-blue-600 font-bold">ubirajara_neto@hotmail.com</span></p>
    </div>
    <div class="mt-4 flex flex-col md:flex-row md:justify-between w-6/12">
      <div class="mb-4">
        <a href="https://dev.to/ubirajaramneto" class="ghost-btn text-2xl font-mono text-gray-800">Blog</a>
      </div>
      <div class="mb-4">
        <a href="https://www.linkedin.com/in/ubirajara-marsicano-neto/" target="_blank" class="ghost-btn text-2xl font-mono text-gray-800">Linked-In</a>
      </div>
      <div class="mb-4">
        <a href="https://www.github.com/ubirajaramneto" target="_blank" class="ghost-btn text-2xl font-mono text-gray-800">Github</a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'home'
}
</script>

<style lang="sass" scoped>
.ghost-btn
  cursor: pointer
  &:after
    content: ""
    display: block
    height: 2px
    width: 10px
    background-color: black
    opacity: .6
    transition: width .15s linear
    will-change: width
  &:hover:after
    width: 100%
</style>
