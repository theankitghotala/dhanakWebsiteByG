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
    justify-content:space-evenly;
    align-items: center;
    height: 70px;
    padding-top: 30px ;
    /* background-color: rgba(255, 255, 255, 0.185); */
    
    /* background-image: url(./assets/5.jpg); */
    /* background-size: cover; */
    /* box-shadow: 0px 5px 15px rgba(0, 0, 0, 0.1); */
  }
  .navbar-left{
    display: flex;
    justify-content: center;
    align-items: center;
    
    
  }
  .navbar-right{
    display: flex;
    justify-content: center;
    align-items: center;
  

  }
  
  .navbar h1 {
    font-size: 36px;
    margin: 10px;
    color: #333;
  }
  
  .navbar a {
    color: #DC3C34;
    text-decoration: none;
    margin:60px;
    font-size: 18px;
    transition: color 0.3s ease;
    font-weight: bold;
  }
  
  .navbar a:hover {
    color: #EC9420;
  }

  .myClickableHeading{
    display: flex;
    justify-content: center;
    align-items: center;
	background: linear-gradient(to right, rgb(255, 115, 0) , rgb(255, 30, 0));
	-webkit-text-fill-color: transparent;
	background-clip: text;
    cursor: default;
  }

  .myClickableHeading:hover {
        cursor: pointer; 
      }
  
  .shape{
    z-index: 2;
    position: absolute;
    display: flex;
    justify-items: center;
    justify-content:space-evenly;
    padding: 10px;
    height: 160px;
    width: 220px;
  }


</style>