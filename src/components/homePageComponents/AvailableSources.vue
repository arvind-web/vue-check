<template>
    <div class="availableSources">
        <p class="heading">Available Sources</p>
        <div class="tabs">
            <button class="btnStyle active">General Analysis</button>
            <button class="btnStyle">Financial Data</button>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
.tabs,
.heading {
    display: flex;
}

.btnStyle {
    margin: 5px 8px 40px 0px;
    width: 165px;
    height: 35px;
    color: black;
    border: 2px solid #3c99ef;
    border-radius: 12px;
    font-weight: bold;
    background: white;
}

.active {
    background-color: #3c99ef;
    color: white;
}

.heading {
    color: #3c99ef;
    font-weight: bold;
}
</style>