<template>
  <div id="restaurant-forum">
    <Navbar />
    <main
      role="main"
      class="mt-5 bg-white"
    >
      <router-view/>
    </main>
  </div>
</template>

<script>
// import bootstrap
import 'bootstrap'
import 'bootstrap/dist/css/bootstrap.min.css'
// bootstrap above
import Navbar from './components/Navbar.vue'
export default {
  name: 'App',
  components: {
    Navbar
  }
}
</script>
