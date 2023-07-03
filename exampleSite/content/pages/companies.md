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
          <img src="exampleSite/static/images/uploads/comp1.png" alt="logotipas">
          <p>Šilko Brizas</p>
      </a>
      <a href="https://verslobrizas.lt/" id="SB">
        <img src="" alt="logotipas">
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


