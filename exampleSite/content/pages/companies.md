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
      <a href="https://livreal.netlify.app/" id="SG">
          <img src="https://verslobrizas.lt/images/livreal.svg" alt="logotipas">
          <p>LivReal</p>
      </a>
      <a href="https://mokslopolis.com/" id="SG">
          <img src="https://verslobrizas.lt/images/mokslopolis.png" alt="logotipas">
          <p>Mokslopolis</p>
      </a>
      <a href="https://getev.eu/" id="SG">
          <img src="https://verslobrizas.lt/images/getev.png" alt="logotipas">
          <p>getEV</p>
      </a>
      <a href="https://helperis.lt/" id="SG">
          <img src="https://verslobrizas.lt/images/helperis.jpg" alt="logotipas">
          <p>Helperis</p>
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
      object-fit: contain;
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


