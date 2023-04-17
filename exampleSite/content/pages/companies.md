---
title: 'Įmonės'
url: "companies"
menu:
  main:
    name: "Įmonės"
    weight: 3
---
<html>
  <div class="collection">
    <div class="companies">
      <a href="google.com" id="SG">
          <img src="/images/cctv.jpeg" alt="Šilko Brizo logotipas">
          <p>Šilko Brizas</p>
      </a>
      <a href="google.com" id="SB">
        <img src="/static/images/uploads/comp2.png" alt="Sukto Gaidžio logotipas">
        <p>Suktas Gaidys</p> 
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
      width: 100%;
      height: 100px;
      filter: grayscale(100%);
      transition: .3s ease-in-out;
    }
    img:hover {
      filter: grayscale(0);
    }
    
    
  
  </style>
</html>


