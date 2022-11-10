<template>
    <div class="recentTrends">
        <p class="heading">Recent Trends</p>
        <div class="trendCards">
            <div class="highlyPositive">
                <span>Highly Positive</span>
                <div class="highlyPositiveMain">
                    <div class="highlyPositiveItems">

                    </div>
                </div>
                
                <!-- <li v-for="item in highlyPositive" :key=item style="color: white">
                    {{ item }}
                    </li> -->
            </div>
            <div class="moderatelyPositive">
                <span>Moderately Positive</span>
                <div class="moderatelyPositiveMain">
                    <div class="moderatelyPositiveItems">

                    </div>
                </div>
            </div>
            <div class="moderatelyNegative">
                <p>Moderately Negative</p>
                <div class="moderatelyNegativeMain">
                    <div class="moderatelyNegativeItems">

                    </div>
                </div>
            </div>
            <div class="highlyNegative">
                <p>Highly Negative</p>
                <div class="highlyNegativeMain">
                    <div class="highlyNegativeItems">

                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {
            highlyPositive: ['Inflation', 'Oracle'],
            moderatelyPositive: ['Michael Jordan', 'Samsung', 'Cisco', 'Caltech', 'Apple Watch'],
            moderatelyNegative: ['Gas Prices', 'Trump', 'Amazon', 'Cristiano Ronaldo', 'Nvidia'],
            highlyNegative: ['Tesla', 'Facebook', 'Biden', 'Nico']
        }
    }
}
</script>

<style scoped>
.heading {
    display: flex;
    color: #3c99ef;
    font-weight: bold;
}

.highlyPositive,
.moderatelyPositive,
.moderatelyNegative,
.highlyNegative {
    box-shadow: 3px 3px lightgrey;
    height: 100px;
    margin: 0px 0px 15px 0px;
    padding: 0px 0px 0px 18px;
    border: 1px solid lightgray;
    display: flex;
}

.highlyPositive p, span,
.moderatelyPositive p,
.moderatelyNegative p,
.highlyNegative p {
    font-size: 14px;
    font-weight: bold;
    color: white
}

.highlyPositiveMain,
.moderatelyPositiveMain,
.moderatelyNegativeMain,
.highlyNegativeMain {
    display: flex;
    justify-content: center;
    align-items: center;
}

.highlyPositiveItems,
.moderatelyPositiveItems,
.moderatelyNegativeItems,
.highlyNegativeItems {
    background: #77c54f;
    height: 30px;
    width: 100px;
    border: solid #77c54f;
    border-radius: 5px;
}
</style>