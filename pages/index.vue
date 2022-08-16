<template>
  <div>
    <Navbar />
    <Heros />
    <Info />
  </div>
</template>

<script>

import Navbar from "../components/Navbar.vue";
import Heros from "../components/Heros.vue";
import Info from "../components/Info.vue";
export default {
  name: 'IndexPage',
  components: {
    Navbar,
    Heros,
    Info
  }
}
</script>
