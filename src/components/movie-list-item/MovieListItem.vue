<template>
    <div>
        <!-- Phase One -->
        <li class="list-group-item d-flex justify-content-between">
            <span class="list-group-item-label">Iron Man (2008)</span>
            <input type="number" class="list-group-item-input" defaultValue="0"  name="" id="">
            <div class="d-flex justify-content-center align-items-center">
                <button type="button" class="btn-cookie btn-sm ">
                    <i class="fas fa-cookie"></i>
                </button>

                <button type="button" class="btn-trash btn-sm ">
                    <i class="fas fa-trash"></i>
                </button>

                <i class="fas fa-star"></i>
            </div>

        </li>
        <li>The Incredible Hulk (2008)</li>
        <li>Iron Man 2 (2010)</li>
        <li>Thor (2011)</li>
        <li>Captain America: The First Avenger (2011)</li>
        <li>The Avengers (2012)</li>

        <!-- Phase Two -->
        <li>Iron Man 3 (2013)</li>
        <li>Thor: The Dark World (2013)</li>
        <li>Captain America: The Winter Soldier (2014)</li>
        <li>Guardians of the Galaxy (2014)</li>
        <li>Avengers: Age of Ultron (2015)</li>
        <li>Ant-Man (2015)</li>

        <!-- Phase Three -->
        <li>Captain America: Civil War (2016)</li>
        <li>Doctor Strange (2016)</li>
        <li>Guardians of the Galaxy Vol. 2 (2017)</li>
        <li>Spider-Man: Homecoming (2017)</li>
        <li>Thor: Ragnarok (2017)</li>
        <li>Black Panther (2018)</li>
        <li>Avengers: Infinity War (2018)</li>
        <li>Ant-Man and The Wasp (2018)</li>
        <li>Captain Marvel (2019)</li>
        <li>Avengers: Endgame (2019)</li>
        <li>Spider-Man: Far From Home (2019)</li>

        <!-- Phase Four -->
        <li>Black Widow (2021)</li>
        <li>Shang-Chi and the Legend of the Ten Rings (2021)</li>
        <li>Eternals (2021)</li>
        <li>Spider-Man: No Way Home (2021)</li>
        <li>Doctor Strange in the Multiverse of Madness (2022)</li>
        <li>Thor: Love and Thunder (2022)</li>
        <li>Black Panther: Wakanda Forever (2022)</li>

        <!-- Marvel Studios TV Shows -->
        <li>WandaVision (2021)</li>
        <li>The Falcon and The Winter Soldier (2021)</li>
        <li>Loki (2021–present)</li>
        <li>What If...? (2021–present)</li>
        <li>Hawkeye (2021)</li>
        <li>Moon Knight (2022)</li>
        <li>Ms. Marvel (2022)</li>
        <li>She-Hulk: Attorney at Law (2022)</li> 
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
    .list-group-item {
        padding: 15px 20px;
        border: none;
        border-bottom: 1px solid #3d5a80;
        background: transparent;

    }
    .list-group-item:last-child {
        border-bottom: none;
    }
    .list-group-item span {
        line-height: 35px; 
        font-size: 20px;
        cursor: pointer;
        width: 550px;
    }

    .list-group-item input {
        line-height: 35px;
        font-size: 20px;
        text-align: center;
        border: 0;
        outline: none
    }

    .list-group-item button {
        width: 35px;
        height: 35px;
        margin: 3px;
        font-size: 17px;
        border: none;
        cursor: pointer;
    }

    .list-group-item .btn-cookie {
        color: #e09f3e;
    }

    .list-group-item .btn-trash {
        color: #e5383b;
    }

    .list-group-item .fa-star {
        width: 35px;
        height: 35px;
        text-align: center;
        line-height: 35px;
        font-size: 16px;
        color: #FFD700;
        transition: 0.3s all;
        transform: translateX(30px);
        opacity: 0;
    }

    .list-group-item.like .fa-star {
        opacity: 1;
        transform: translateX(0);
    }

    .list-group-item.favourite .list-group-item-label,
    .list-group-item.favourite .list-group-item-input {
        color: #ffd700;
    }

</style>