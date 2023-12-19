<template>
    <div id="start">
     <h1>לומדת <br> אסטרואיד</h1>
     <button class="button">התחל</button>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        name: 'start',
        message: 'Hello, Vue 3!',
      };
    },
    
  };
  </script>
  
  <style scoped>
  
  @font-face {
    font-family: 'YourFont'; /* Define the font-family name */
    src: url('/assets/Rubik-VariableFont_wght.ttf') format('woff'); /* Adjust the file path */
    font-weight: normal;
    font-style: normal;
  }
  
  /* Your styles go here */
  #start {
    background-image: url('/adjustedBg.jpg');
    background-size: cover; /* Adjust this based on your needs */
    margin: 0; /* Reset default body margin */
    height: 90vh;
    width: 100vw;
    font-family: 'YourFont', sans-serif;
  }
  
  h1{
    text-align: center;
    color: white;
    padding-top: 15vh;
    font-size: 14vw;
  }
  
  .button {
    position: absolute;
    left: 40%;
    top:80%;
    display: inline-block;
    padding: 15px 25px;
    font-size: 24px;
    cursor: pointer;
    text-align: center;
    text-decoration: none;
    outline: none;
    color: #fff;
    background-color:#096a75;
    border: none;
    border-radius: 15px;
    box-shadow: 0 9px #999;
  }
  
  .button:hover {background-color: #119ead}
  
  .button:active {
    background-color: #119ead;
    box-shadow: 0 5px #666;
    transform: translateY(4px);
  }
  </style>
  