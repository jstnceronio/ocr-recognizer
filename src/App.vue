<template>

  <div class="container grid grid-cols-4 grid-rows-4 gap-y-1 gap-px">
    <Header />
    <TextContent />
    <UploadContent />
    <Footer />
  </div>
  
</template>

<script>

 import Header from './components/Header'
 import TextContent from './components/TextContent'
 import UploadContent from './components/UploadContent'
 import Footer from './components/Footer'

export default {
  name: 'App',
  components: {
    Header,
    TextContent,
    UploadContent,
    Footer,
  },
}
</script>

<style src="./assets/tailwind.css" />
