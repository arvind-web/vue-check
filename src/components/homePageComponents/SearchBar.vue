<template>
    <div class="searchBar">
        <h1>Photon Search</h1>
        <div class="searchTextClass">
            <input type="text" name="searchText" id="searchText" placeholder="Search Topic of Interest"/>
            <br/>
            <button id="searchBtn">Search Insights</button>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
    h1 {
        color: #56ccf2;
    }

    #searchText {
        width: 50%;
        height: 30px;
        border: 1px solid lightgrey;
        border-radius: 5px;
    }

    #searchBtn {
        margin: 40px 0px 40px 0px;
        width: 130px;
        height: 45px;
        color: white;
        background: #3c99ef;
        border: 0px;
        border-radius: 5px;
    }
</style>