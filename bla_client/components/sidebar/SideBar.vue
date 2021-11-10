<template>
  <div class="fixed top-0 left-0 h-screen w-20 flex flex-col bg-gray-900 text-white shadow-lg">
      <SideBarIcon :tableName="  'Mesa Nº1'  " :icon="  'utensils'  " />
      <SideBarIcon :tableName="  'Mesa Nº2'  " :icon="  'utensils'  " />
      <SideBarIcon :tableName="  'Mesa Nº3'  " :icon="  'utensils'  " />
      <SideBarIcon :tableName="  'Mesa Nº4'  " :icon="  'utensils'  " />
      <SideBarIcon :tableName="  'Mesa Nº5'  " :icon="  'utensils'  " />
      <SideBarIcon :tableName="  'Mesa Nº6'  " :icon="  'utensils'  " />
      <hr class="sidebar-hr">
      <SideBarIcon :tableName="  'Crear Mesa'  " :icon="  'plus'  "/>

  </div>
</template>

<script>
import SideBarIcon from './SideBarIcon.vue'
export default {
  components: {
    SideBarIcon
  }
}
</script>

<style>

</style>