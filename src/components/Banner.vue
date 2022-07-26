<template>
  <div id="main_banner">
    <h1>Make Your Burger</h1>  
  </div>
</template>
<script>
export default {
  name: "Banner",
};
</script>
<style scoped>
#main_banner {
    background-image: url('http://localhost:8080/img/burger.jpg');
    background-position: 0 -250px;
    background-size: cover;
    height: 500px;
    display: flex;
    background-repeat: no-repeat;
    align-items: center;
    justify-content: flex-start;    
}

#main_banner h1 {
  color: #FFF;
  text-align: center;
  font-size: 60px;
  background-color: #222;
  padding: 20px 40px;
}
</style>