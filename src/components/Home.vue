<template>
  <div>
    <div class="center">
      <div class="center-text">
        AUTOMATE <span class="pillar">I</span>
      </div>
      <div class="center-text">
        INTERGRATE <span class="pillar">I</span>
      </div>  
      <div class="center-text">
        SCALE <span class="pillar">I</span>
      </div>
    </div>
    <div class="center-sentence">
      LEADING-EDGE TECHNOLOGY SOLUTIONS FOR SUSTINABLE DIGITAL TRANSFORMATION
    </div>
    <img class="main-image" src="../assets/digital landing.jpg">
  </div>

  <div class="text-question">
    ARE YOU LOOKING TO BUILD, EXPAND, OR MODERNIZE? WE HAVE THE PERFECT DIGITAL SOLUTION FOR YOU
  </div>
  <div class="text-description">
    We leverage advanced technology to address challenges faced by global enterprises in building their digital infrastructure to facilitate better practices and improve customer interactions. Our building Blocks model ensures that we create modular solutions which help you scale and achieve your business ambitions.
  </div>

  <div>
    <div class="city">
      <div class="city-box left-box">
        <span class="city-left-box">DISCOVER THE RIGHT SOLUTION FOR YOU</span>
      </div>
      <div class="city-box city-box-interactive">
        <div class="city-box-text">
          <div class="city-text">DIGITAL STRATIGY</div>
        </div>
        <button class="learn-button">Learn More</button>
      </div>
      <div class="city-box city-box-interactive">
        <div class="city-box-text">
          ENTERPRISE SOFTWARE
        </div>
        <button class="learn-button">Learn More</button>
      </div>
    </div>
    <img class="city-image" src="../assets/cityscape.jpg">
  </div>
  <div class="text-question">
    STAY IN TOUCH
  </div>
  <div class="text-description">
    Subscribe to recieve our latest updates and insights
  </div>


  <div class="input-group mb-3">
    <input type="text" class="email-input" placeholder="E-MAIL" aria-label="Recipient's username">
    <button class="btn btn-outline-info" type="button">SIGN UP</button>
  </div>

  <div class="bottom-image-container">
    <div class="bottom-text-top">
      UNLOCK THE WORLD OF POSSIBILITES
    </div>
    <div class="bottom-text">
      TRANSFORM <span class="pillar">I</span>
    </div>
    <img class="bottom-image" src="../assets/digital landing.jpg">
  </div>

  <nav class="navbar navbar-expand-lg">
  <div class="container-fluid">
    <a class="nav-link active" aria-current="page" href="#">
      <img class="logo" src="../assets/Motif transparent.png">
    </a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <p class="logo-name" ><span class="c-circle">C</span> 2024 Lytus Digital</p>
          </li>
          
      </ul>
        <div class="center-image">
          <img class="logo-image" src="../assets/X.png">
          <img class="logo-image" src="../assets/X.png">
          <img class="logo-image" src="../assets/X.png">
          <img class="logo-image" src="../assets/X.png">
        </div>
        <div>
          <p class="company-name">LYTUS DIGITAL PRIVATE LIMITED</p>
          <p class="company-address">1210 C Wing, One BKC, Bandra (E) Mumbai 400051</p>
        </div>
    </div>
  </div>
</nav>


</template>

<script>
export default {
  name: 'Home'
}
</script>

<style scoped>

  .main-image {
    width: 100%;
    height: 500px;
    object-fit: cover;
    opacity: 0.3;
  }
  .center {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
    font-size: 25px;
    z-index: 2;
  }
  
  .pillar {
    margin: 15px;
    font-size: 35px;
    font-weight: bold;
    color: cyan;
  }

  .center-sentence {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    position: absolute;
    width: 100%;
    height: 100%;
    top: 3;
    font-size: 30px;
    z-index: 2;
  }

  .text-question {
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 25px;
    margin: 30px;
  }

  .text-description {
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 20px;
    margin-left: 20px;
    margin-bottom: 30px;
  }

  .city-image {
    width: 100%;
    height: 600px;
    object-fit: cover;
    opacity: 0.3;
  }

  .city {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    position: absolute;
    width: 100%;
    height: 100%;
    font-size: 24px;
  }

  .city-box {
    margin: 30px;
    width: 350px;
    height: 60vh;
    border: 2px solid white;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    z-index: 1;
    border-radius: 4px;
    transition: background-color 0.2s;
  }

  .city-box:hover {
    background-color: #00ffff59;
  }
  .left-box {
    background-color: black;
  }

  .city-left-box {
    margin: 45px;
    padding-left: 15px;
    padding-bottom: 15px;
    border-bottom: 2px solid cyan; 
  }

  .city-text {
    display: flex;
    position: relative;
    z-index: 4;
  }

  .city-box-text {
    display: flex;
    margin-top: 160px;
  }

  .learn-button {
    margin-top: 130px;
    background-color: transparent;
    color: white;
    border: 1px solid cyan;
    border-radius: 2px;
    padding-left: 70px;
    padding-right: 70px;
    font-size: 18px;
  }

  .input-group {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    width: 500px;
    margin-left: 425px; 
  }

  .email-input {
    display: flex;
    flex: 1;
    background-color: black;
    padding-left: 10px;
    padding-top: 5px;
    padding-bottom: 5px;
    color: white; 
  }
  
  ::placeholder {
    color: white;
  }

  .bottom-image {
    width: 100%;
    height: 400px;
    object-fit: cover;
    opacity: 0.3;
  }

  .bottom-image-container {
    margin-top: 30px;
    background-color: #00ffff59;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    width: 100%;
    height: 100%;
    font-size: 25px;
    z-index: 1;
  }

  .bottom-text-top {
    display: flex;
    justify-content: center;
    align-items: center;
    position: absolute;
    z-index: 4;
    margin-bottom: 250px;
    font-size: 25px;
  }

  .bottom-text {
    display: flex;
    justify-content: center;
    align-items: center;
    position: absolute;
    z-index: 4;
  }

  .navbar {
    background-color: #0d1818;
    z-index: 10;
 }

 .logo {
    cursor: pointer;
    width: 100px;
    height: 70px;
    object-fit: contain;
  }

  .logo-name {
    margin-top: 17px; 
  }

  .logo-image {
    width: 100px;
    height: 30px;
    object-fit: contain;
    color: white;
  }

  .company-name {
    font-size: 16px;
    font-weight: bold;
    color: white;
    margin: 10px;
  }

  .company-address {
    font-size: 16px;
    color: white;
    margin: 10px;
  }

  .c-circle {
    padding-left: 4px;
    padding-right: 4px;
    padding-bottom: 1px;
    border: 2px solid white;
    border-radius: 13px;
    font-size: 11px; 
  }

  .center-image {
    margin-right: 100px;
  }

</style>