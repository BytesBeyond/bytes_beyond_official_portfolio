<template>
  <FilterMenu/>
</template>

<script lang="ts">
import Vue from 'vue'
import FilterMenu from "~/components/FilterMenu.vue";

export default Vue.extend({
  name: 'IndexPage',
  components: {FilterMenu}
})
</script>
