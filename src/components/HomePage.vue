<template>
  <div class="home">
    <SearchBar />
    <AvailableSources />
    <RecentTrends />
  </div>
</template>

<script>
import SearchBar from './homePageComponents/SearchBar.vue'
import AvailableSources from './homePageComponents/AvailableSources.vue'
import RecentTrends from './homePageComponents/RecentTrends.vue'

export default {
  name: 'home-page',
  components: {
    SearchBar,
    AvailableSources,
    RecentTrends
  }
}
</script>

<style scoped>
.home {
  margin: auto;
  width: 50%;
  padding: 65px 0px 65px 0px;
}
</style>
