<template>
  <div class="home">
     <div>
      <img class="image" src="../assets/Logo2.jpg" aria-hidden="true" />
    </div>
    <div class="to-appstore">
      <a href= "https://philips.team-hp.com/pregnancy-new" target="_blank">
        <img src="..//assets/playstore.svg" target="_blank" />
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomePage',
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped >
.home{
  display: flex;
  flex-wrap: wrap;
  justify-content: center; 
}
.image{
  border-radius: 10px;
  width: 100%;
  max-width: 500px;
  height: auto; 
}
.to-appstore{
  padding-top: 50px;
  width:70%;
  max-width: 300px;
  height: auto;
}

</style>
