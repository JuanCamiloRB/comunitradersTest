
<template>
     <div id="home"></div>
<!-- Start navbar -->
     <div class="navbar">
      <div class="navbar-left">
        <img src="../assets/Logo.svg"/>
      </div>
      <div class="navbar-middle">
        <ul>
          <li><a href="#">FOREX</a></li>
          <li><a href="#">STOCKS</a></li>
          <li><a href="#">FUTURES</a></li>
          <li><a href="#">TradeGATEHub</a></li>
        </ul>
      </div>
      <div class="navbar-right">
        <ul>
          <li class="dropdown">
            <a href="#">Log in</a>
            <div class="dropdown-content">
              <a href="#">Suboption 1</a>
              <a href="#">Suboption 2</a>
              <a href="#">Suboption 3</a>
            </div>
          </li>
          <li><a href="#">Contact Us</a></li>
          <li class="dropdown">
            <a href="#">English</a>
            <div class="dropdown-content">
              <a href="#">Suboption 4</a>
              <a href="#">Suboption 5</a>
            </div>
          </li>
        </ul>
      </div>
    </div>
<!-- finish navbar -->


        <div class="landing-page">
        <div class="left-section">
            <img src="../assets/Mask Group 1.png" alt="Left Background Image" />
            <!-- Content for the left section goes here -->
        </div>
        <div class="right-section">
            <div class="content">
        <h1><img class ="custom.title" src="../assets/Group 30.png" alt="Left Background Image" /></h1>
        <div class="title-separator"></div> <!-- Line separating the title and main description -->
        <p class="main-description">  Tradeview’s CommuniTraders software lets our partners provide value-added copy trading to their clients.</p>
        <div class="buttons">

          <p class="button-descriptionl">  
            Free Download for Tradeview Users
          <button 
            class="buttons-left">Contact your Broker
            <span class="button-description"></span>
         </button>
         </p>
         <div class="separator-line"></div> 
         <p class="button-descriptionr">  
          Don’t have a Tradeview Account yet?
          <button 
             class="buttons-right">Get a Free Demo
           
          </button>
        </p>
        </div>
    </div>

            <!-- Content for the right section goes here -->
        </div>
        </div>
  </template>
  
  <script>
  export default {
    name: 'LandingPage',
  };
  </script>
  
  <style scoped>
  .landing-page {
    display: flex;
    flex-wrap: wrap; /* Allow flex items to wrap to the next line on small screens */
  }
  
  .left-section,
  .right-section {
    flex: 1;
  min-height: 50vh; /* Set a minimum height for each section */
  display: flex;
  justify-content: center;
  align-items: center;
  color: #b17373; /* Set the text color */
  font-size: 24px; /* Set the font size */

  }
  
  .left-section {
   
    background-image: url("../assets/Mask Group 1.png");
    width: 840px;
  }
  
  .right-section {
    background-color: #181F29;  /* Set the background color for the left section */ 
    width: 1079px;
  }

  .content {
  text-align: center;
}

.title-separator {
  margin-left: 212px;
  margin-right: 212px;
  height: 2px;
  width: 654px; /* Width of the line separating title and main description */
  background-color: #ffffff;
  margin: 0px 150px; /* Adjust margin as needed */
  text-align: center;
}
.main-description {
  margin-bottom: 20x; /* Space between the main title and description */
  margin-top: 98.63px; /* Updated top margin */
  margin-left: 207px; /* Updated left margin */
  margin-right: 207px; /* Updated left margin */
  /* Updated width */
  height: 129px; /* Updated height */
  font: var(--unnamed-font-style-normal) normal var(--unnamed-font-weight-300) var(--unnamed-font-size-32)/var(--unnamed-line-spacing-43) var(--unnamed-font-family-noto-sans);
  letter-spacing: var(--unnamed-character-spacing-0);
  text-align: center;
  font: normal normal 300 32px/43px Noto Sans;
  letter-spacing: 0px;
  color: #FFFFFF;
}

.custom-title {
  margin-top: 346px;
  margin-left: 1170px;
  width: 420px;
  height: 118px;
}

.buttons {
  margin-top: 20px;
  display: flex;
  justify-content: center;
}

.buttons button {
  margin: 0 72px;
  padding: 10px 20px;
  font-size: 20px;
  justify-content: center;
  cursor: pointer;

}

.button-title {
  display: block;
}

.button-descriptionr button,
.button-descriptionl button {
  margin-top: 26px; /* Space between the title and description */
}

.button-descriptionr {
  
  font: var(--unnamed-font-style-normal) normal var(--unnamed-font-weight-300) 18px/24px var(--unnamed-font-family-noto-sans);
  letter-spacing: var(--unnamed-character-spacing-0);
  text-align: center;
  font: normal normal 300 18px/24px Noto Sans;
  letter-spacing: 0px;
  color: #FFFFFF;
  opacity: 1;
}

.button-descriptionl {

  font: var(--unnamed-font-style-normal) normal var(--unnamed-font-weight-300) 18px/24px var(--unnamed-font-family-noto-sans);
  letter-spacing: var(--unnamed-character-spacing-0);
  text-align: center;
  font: normal normal 300 18px/24px Noto Sans;
  letter-spacing: 0px;
  color: #FFFFFF;
  opacity: 1;
}

.buttons-right {
  margin-left: 227px;
  width: 240px;
  height: 55px;
  display: flex;
  justify-content: center;
  background: var(---ff0000) 0% 0% no-repeat padding-box;
  background: #FF0000 0% 0% no-repeat padding-box;
  opacity: 1;
  color: #ffffff;
  font-size: 27px;
  text-align: center;
}

.separator-line {
  height: 164px;
  width: 2px;
  background-color: #ffffff;
  margin: 0 40px; /* Adjust the margin as needed */
}

.buttons-left {
  margin-left: 227px;
  width: 240px;
  height: 55px;

}
.navbar {
  height: 119px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #333;
  padding: 10px;
  color: white;
  font-family: 'Your Font', sans-serif; /* Replace 'Your Font' with the actual font name */
  letter-spacing: 1px;
}

.navbar-left img {
  width: 364.9px; /* Adjust the width of your logo */
  height: 55.8px; /* Maintain aspect ratio */
}

.navbar-middle ul,
.navbar-right ul {
  list-style: none;
  padding: 0;
  margin: 0;
  display: flex;
}

.navbar-middle li,
.navbar-right li {
  margin: 0 10px;
}

.navbar-middle a,
.navbar-right a {
  text-decoration: none;
  color: white;
  font-size: 16px;
  transition: color 0.3s ease;
}

.navbar-middle a:hover,
.navbar-right a:hover {
  color: #2ecc71; /* Change the color on hover */
}

.dropdown {
  position: relative;
  display: inline-block;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: #333;
  min-width: 160px;
  box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
  z-index: 1;
}

.dropdown-content a {
  color: white;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  transition: background-color 0.3s ease;
}

.dropdown-content a:hover {
  background-color: #2ecc71; /* Change the background color on hover */
}

.dropdown:hover .dropdown-content {
  display: block;
}
  
  /* Add more styling as needed */
  
  /* Responsive styling for smaller screens */
  @media screen and (max-width: 768px) {
    .left-section,
  .right-section {
    flex: 1 100%;
    min-height: 30vh;
    width: auto; /* Reset the width on smaller screens */
  }

  .custom-title {
    margin: 20px 0;
  }

  .buttons button {
    font-size: 16px;
    margin-left: 0;
  }
  }
  </style>