<template>
  <div class="sidebar-icon group" >
      <font-awesome-icon 
      :icon="['fas', icon]" />
        <span class="sidebar-tooltip group-hover:scale-100" >
            {{ tableName }}
        </span>
  </div>
</template>

<script>

export default {
    props: [
        'icon',
        'tableName'
    ]
}
</script>

<style>

</style>