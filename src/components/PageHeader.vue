<template>
    <div class="header">
        <div class="navBar" id="topNav">
            <div class="reqPages">
              <p>My Photon</p>
              <p>Photon Live</p>
              <p>Comparison</p>
              <p>Home</p>
            </div>
            <div class="brandName">
              <h3>Photon Insights</h3> 
            </div>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
.reqPages p,
.brandName h3{
  float: right;
  color: #56ccf2;
  padding: 0px 12px;
}

.brandName h3{
  float: left;
}

.reqPages p:hover {
  cursor: pointer;
  background-color: #358dee;
  color: white;
}

.brandName h3{
  cursor: pointer;
}
</style>