<template>
  <div>
    <Navbar/>
    <Banner/>
    <Search/>
    <Destinations/>
    <Tour/>
    <Trending/>
    <Offers/>
    <Footer/>
  </div>
</template>

<script>
import Destinations from '../components/Destinations.vue'
import Trending from '../components/Trending.vue'
export default {
  components: { Trending, Destinations },
  name: 'IndexPage'
}
</script>
