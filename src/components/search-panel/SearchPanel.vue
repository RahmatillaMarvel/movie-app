<template>
    <div>
        <input type="text" class="form-control search-input" placeholder="Search movies: " name="" id="">
    </div>
</template>
<script>
export default {
    name: 'SearchPanel'
}
</script>
<style scoped>
    .search-input {
        margin-bottom: 1rem;
        padding: 1.5rem;
        background-color: #fcfaf5;
        border-radius: 4px;
        box-shadow: 15px 15px 15px rgba(0, 0, 0, 0.15);
        
    }
</style>