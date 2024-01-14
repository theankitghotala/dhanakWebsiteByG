<template>
    <nav class="navbar">
    <div class="navbar-left">
       
            <img id="myClickableHeading" src="./assets/dhanak_logo.png" width="113" height="80">
            <img id="myClickableHeading" src="./assets/dhanak.png" width="140" height="40">
            
    </div>
    <div class="navbar-right">
      <a href="#signup">Sign Up</a>
      <a href="#login">Log In</a>
      <a href="#events">Events</a>
      <a href="#sponsors">Sponsors</a>
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
    .navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: rgba(255, 255, 255, 0.9);
    backdrop-filter: blur(10px);
    padding: 10px;
    box-shadow: 0px 5px 15px rgba(0, 0, 0, 0.1);
  }
  .navbar-left{
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-left: 20px;
  }
  .navbar-right{
    margin-right: 50px;
  }
  
  .navbar h1 {
    font-size: 36px;
    margin: 10px;
    color: #333;
  }
  
  .navbar a {
    color: #333;
    text-decoration: none;
    margin-left: 20px;
    transition: color 0.3s ease;
    font-weight: bold;
  }
  
  .navbar a:hover {
    color: #ff9068;
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
</style>