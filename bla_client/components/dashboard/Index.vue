<template>
  <div class="flex container mx-auto object-center">
      <NuxtLogo />
      <SideBar />
  </div>
</template>

<script>
import NuxtLogo from '../NuxtLogo'
import SideBar from '@/components/sidebar/SideBar.vue'

export default {
    components: {
        NuxtLogo,
        SideBar
    }
}
</script>

<style>

</style>