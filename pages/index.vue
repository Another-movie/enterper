<template>
  <div>
    <Header />
    <div>
      <img src='@/assets/main_block.jpg' alt=''>
    </div>
    <div>
      <img src='@/assets/why_block.jpg' alt=''>
    </div>
    <div>
      <img src='@/assets/why_block.jpg' alt=''>
    </div>
    <div>
      <img src='@/assets/teacher_block.png' alt=''>
    </div>
    <div>
      <img src='@/assets/educ_block.jpg' alt=''>
    </div>
    <div>
      <img src='@/assets/contact_block.jpg' alt=''>
    </div>
    <div>
      <img src='@/assets/mobile_app.jpg' alt=''>
    </div>
    <div>
      <img src='@/assets/footer.jpg' alt=''>
    </div>
  </div>
</template>

<script>
import Header from '~/components/Base/Header'
export default {
  components: { Header },
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
}

body {
  margin: 0;
  padding: 0;
}

img {
  width: 100%;
  object-fit: cover;
}
</style>
