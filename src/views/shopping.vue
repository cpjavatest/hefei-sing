<template>
  <div>
    <Header></Header>
    <Nav :index="5"></Nav>
    <div class="content">
      shopping
    </div>
    <Bottom></Bottom>
  </div>
</template>

<script>
  import Header from '@/components/header'
  import Nav from '@/components/nav'
  import Bottom from '@/components/bottom'

  export default {
    name: "shopping",
    components: {
      Header,
      Nav,
      Bottom
    }
  }
</script>

<style scoped>

</style>
