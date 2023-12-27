<template>
  <div class="app">
    <div class="content">
      <AppInfo/>
      <div class="search-panel">
        <SearchPanel/>

      </div>
    </div>
  </div>
</template>

<script>
import AppInfo from './components/app-info/AppInfo.vue';
import SearchPanel from './components/search-panel/SearchPanel.vue';
export default {
  name: 'App',
  components: {
    AppInfo,
    SearchPanel,
    

  }
}
</script>

<style scoped>
.app{
  height: 100vh;
  color: #000;
}

.content{
  width: 1000px;
  min-height: 700px;
  background-color: #fff;
  margin: 0 auto;
  padding: 5rem 0;
}
.search-panel{
  margin-top: 2rem;
  padding: 1.5rem;
  background-color: #fcfaf5;
  border-radius: 4px;
  box-shadow: 15px 15px 15px rgba(0, 0, 0, 0.15);
}
</style>
