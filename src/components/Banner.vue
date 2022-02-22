<template>
  <div id="main-banner">
    <h1>Make Your Burger</h1>
    <!--Let browser know website is optimized for mobile-->
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  </div>
</template>

<script>
export default {
  name: "Banner",
};
</script>

<style scoped>
#main-banner {
  background-image: url("/img/burger.jpg");
  background-position: 0 -500px;
  background-size: cover;
  height: 500px;
  display: flex;
  align-items: center;
  justify-content: flex-start;
  width: 100%;
  object-fit: cover;
}
@media only screen and (max-width: 1500px) {
  #main-banner {
    background-position: 0 -200px;
    background-size: cover;
    height: 500px;
    display: flex;
    align-items: center;
    justify-content: flex-start;
    width: 100%;
    /* display: none;*/
  }
}

@media only screen and (max-width: 1040px) {
  #main-banner {
    background-position: 0 -100px;
    background-size: cover;
    height: 500px;
    display: flex;
    align-items: center;
    justify-content: flex-start;
    width: 100%;
  }
}

@media only screen and (max-width: 860px) {
  #main-banner {
    background-position: 0 -10px;
    background-size: cover;
    height: 500px;
    display: flex;
    align-items: center;
    justify-content: flex-start;
    width: 100%;
  }
}

#main-banner h1 {
  color: #fff;
  text-align: center;
  font-size: 60px;
  background-color: #222;
  padding: 20px 40px;
}
</style>
