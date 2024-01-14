<template>
  <div class="logo">
    <div class="shape">
      <img id="myClickableHeading" src="./assets/dhanak_logo.png"> 
    </div>
  </div>
    <nav class="navbar">
      <div class="navbar-left">
        <a href="#events">Events</a>
      <a href="#sponsors">Sponsors</a>
        
      </div>
    <div class="navbar-right">
      <a href="#signup">Sign Up</a>
        <a href="#login">Log In</a>
    </div>
  </nav>
</template>

<script>
    export default {
  name: 'navBar',
  props: {
    msg: String
  }
}

</script>



<style scoped>
    .logo{
      z-index: 1;
      display: flex;
      justify-content: center;
      justify-items: center;
    }
    .navbar {
      position: relative;
      z-index: 1;
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 130px;
    width: 100%;
    background-color: aliceblue;
    /* background-image: url(./assets/navbar.jpg); */
    background-size: cover;
    padding: 10px;
    box-shadow: 0px 5px 15px rgba(0, 0, 0, 0.1);
  }
  .navbar-left{
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    margin-left: 280px;
  }
  .navbar-right{
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    margin-right: 280px;
  }
  
  .navbar h1 {
    font-size: 36px;
    margin: 10px;
    color: #333;
  }
  
  .navbar a {
    background: linear-gradient(90deg, #1e39a5, #c50e07);
  background-size: auto;
  background-clip: border-box;
  -webkit-background-clip: text;
  background-clip: text;
  background-size: 300% 300%;
  -webkit-text-fill-color: transparent;
    color: #333;
    font-size: 20px;
    text-decoration: none;
    margin-left: 20px;
    transition: color 0.3s ease;
    font-weight: bold;
  }
  
  .navbar a:hover {
    color: #DC3C34;
  }
  #myClickableHeading{
	background: linear-gradient(to right, rgb(255, 115, 0) , rgb(255, 30, 0));
	-webkit-text-fill-color: transparent;
	background-clip: text;
    cursor: default;
  }

  #myClickableHeading:hover {
        cursor: pointer; 
      }
  
  .shape{
    z-index: 2;
    position: absolute;
    background-image: url(./assets/navbar.jpg);
    background-size: cover;
    display: flex;
    justify-items: center;
    justify-content:space-evenly;
    padding: 10px;
    height: 150px;
    width: 220px;
    background-color: aliceblue;
    clip-path: polygon(20% 0%, 81% 0, 100% 100%, 0% 100%);
  }


</style>