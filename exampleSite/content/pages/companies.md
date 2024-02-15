---
title: 'Įmonės'
url: "companies"
description: "Įmonės"
menu:
  main:
    name: "Įmonės"
    weight: 3
---
<html>
  <div class="collection">
    <div class="companies">
      <a href="https://silkobrizas.company.site/" id="SG">
          <img src="https://verslobrizas.lt/images/comp1.png" alt="logotipas">
          <p>Šilko Brizas</p>
      </a>
      <a href="https://silkobrizas.company.site/" id="SG">
          <img src="https://verslobrizas.lt/images/comp1.png" alt="logotipas">
          <p>Šilko Brizas</p>
      </a>
      <a href="https://getev.eu/" id="SG">
          <img src="https://verslobrizas.lt/images/comp1.png" alt="logotipas">
          <p>getEV.eu</p>
      </a>
      <a href="https://helperis.lt/" id="SG">
          <img src="https://verslobrizas.lt/images/comp1.png" alt="logotipas">
          <p>getEV.eu</p>
      </a>
      <a href="https://fittimitti.lt/" id="SG">
          <img src="https://verslobrizas.lt/images/comp1.png" alt="logotipas">
          <p>FittiMitti.lt</p>
      </a>
      <a href="https://verslobrizas.lt/" id="SB">
        <img src="" alt="">
        <p></p> 
      </a>
    </div>
  </div>
  
  
  
  
  
  
  <style>
    #SG, #SB{
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-decoration: none;
    }
    .collection{
      width: 100%; 
    }
    .companies{
      display: flex;
      align-items: center;
      justify-content: space-around;
      
    }

    .companies img{
      width: 10rem;
      height: 10rem;
      filter: grayscale(100%);
      transition: .3s ease-in-out;
    }
    img:hover {
      filter: grayscale(0);
    }
     
      @media (max-width: 576px){
      .companies{
        flex-direction: column;
        
      }    
  
  </style>
</html>


