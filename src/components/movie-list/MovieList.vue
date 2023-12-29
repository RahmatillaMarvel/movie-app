<template>
    <ul class="movie-list list-group">
        <MovieListItem v-for="movie in movies" :movie="movie" />

    </ul>
</template>

<script>
    import MovieListItem from '../movie-list-item/MovieListItem.vue'

    export default {
        components: {
            MovieListItem
        },
        data() {
            return {
                movies: [{
                        name: 'Iron Man',
                        viewers: 2500,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'The Incredible Hulk',
                        viewers: 2200,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Iron Man 2',
                        viewers: 2300,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Thor',
                        viewers: 2100,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Captain America: The First Avenger',
                        viewers: 2000,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'The Avengers',
                        viewers: 2800,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Iron Man 3',
                        viewers: 2600,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Thor: The Dark World',
                        viewers: 2000,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Captain America: The Winter Soldier',
                        viewers: 2400,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Guardians of the Galaxy',
                        viewers: 2700,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Avengers: Age of Ultron',
                        viewers: 2900,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Ant-Man',
                        viewers: 2200,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Captain America: Civil War',
                        viewers: 3000,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Doctor Strange',
                        viewers: 2300,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Guardians of the Galaxy Vol. 2',
                        viewers: 2700,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Spider-Man: Homecoming',
                        viewers: 2600,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Thor: Ragnarok',
                        viewers: 2500,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Black Panther',
                        viewers: 2800,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Avengers: Infinity War',
                        viewers: 3100,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Ant-Man and The Wasp',
                        viewers: 2400,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Captain Marvel',
                        viewers: 2900,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Avengers: Endgame',
                        viewers: 3300,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Spider-Man: Far From Home',
                        viewers: 2700,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Black Widow',
                        viewers: 2500,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Shang-Chi and the Legend of the Ten Rings',
                        viewers: 2800,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Eternals',
                        viewers: 2700,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Spider-Man: No Way Home',
                        viewers: 3200,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Doctor Strange in the Multiverse of Madness',
                        viewers: 3000,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Thor: Love and Thunder',
                        viewers: 2900,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Black Panther: Wakanda Forever',
                        viewers: 2800,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'WandaVision',
                        viewers: 1800,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'The Falcon and The Winter Soldier',
                        viewers: 1900,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Loki',
                        viewers: 2000,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'What If...?',
                        viewers: 1700,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Hawkeye',
                        viewers: 1800,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Moon Knight',
                        viewers: 1900,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Ms. Marvel',
                        viewers: 2000,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'She-Hulk: Attorney at Law',
                        viewers: 2100,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Ant-Man and the Wasp: Quantumania',
                        viewers: 3000,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Guardians of the Galaxy Vol. 3',
                        viewers: 3100,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'The Marvels',
                        viewers: 3200,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Blade',
                        viewers: 2500,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Captain America: New World Order',
                        viewers: 2600,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Thunderbolts',
                        viewers: 2700,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Fantastic Four',
                        viewers: 2800,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Avengers: The Kang Dynasty',
                        viewers: 2900,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Avengers: Secret Wars',
                        viewers: 3000,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Ironheart',
                        viewers: 2000,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Armor Wars',
                        viewers: 2100,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Secret Invasion',
                        viewers: 2200,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Echo',
                        viewers: 2300,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Agatha: House of Harkness',
                        viewers: 2400,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'Daredevil: Born Again',
                        viewers: 2500,
                        favourite: false,
                        like: false
                    },
                    {
                        name: 'X-Men \'97',
                        viewers: 2600,
                        favourite: false,
                        like: false
                    }
                ]


            }
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