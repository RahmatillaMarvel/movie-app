<template>
    <ul class="movie-list list-group">
        <MovieListItem />
        <MovieListItem />
        <MovieListItem />
    </ul>
</template>

<script>
import MovieListItem from '../movie-list-item/MovieListItem.vue'

export default {
    components: {
        MovieListItem
    }    
}
</script>
<style scoped>
    .movie-list {
        margin-top: 2rem;
        margin-bottom: 2rem;
        background-color: #fcfaf5;
        border-radius: 4px;
        box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
        padding: 1.5rem;
    }
</style>