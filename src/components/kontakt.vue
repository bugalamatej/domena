<template>
<div class="container d-flex flex-column justify-content-center">
  <nav id="navbar-example3" class="navbar navbar-light bg-light flex-column align-items-stretch p-3 sticky-top">
    <a class="navbar-brand" href="#">Bugy <span>Detailing</span></a>
    <nav class="nav nav-pills d-flex justify-content-center">
      <a class="nav-link" href="#item-1">Kontakt</a>
      <a class="nav-link" href="#item-2">Interiér</a>
      <a class="nav-link" href="#item-3">Exteriér</a>
      <a class="nav-link" href="#foto">Fotogaléria</a>
 

    </nav>
  </nav>
  <div class="container">
    <navigacia class="">
      <div style="text-align: center;">
        <p class="uvodny">Oživte krásu vášho vozidla s naším profesionálnym detailom!</p>
      </div>
    </navigacia>
    
    <div class="image">
      <img  class="obr" src="../assets/main.png" alt="">
    </div>
    <hr>
    <div class="text-center">
      <h2 id="item-2" class=" heading">Naše služby <span class="bold">Interiér</span></h2>
    </div>
    <div class="row carti">
      <div class=" d-flex justify-content-center row ">
          <div class="card col-2 m-3" style="width: 18rem;">
            <img class="card-img-top" src="../assets/interier.jpg" alt="Card image cap">
            <div class="card-body">
              <h5 class="card-title">Interiér</h5>
              <p class="card-text"> Kompletná renovácia interieru</p>
              <div class="d-flex justify-content-between">
                <a  class="btn btn-primary" href="#item-1">Kontaktovat</a>
                <a href="#interier" class="btn btn-primary">Viac info</a>
              </div>
            </div>
          </div>
          
          
<hr>

<div class="text-center">
  <h2 id="item-3" class=" heading">Naše služby <span class="bold">Exteriér</span></h2>
</div>
<div class="row carti">
  <div class=" d-flex justify-content-center row ">

      
      <div class="card m-3 col-2" style="width: 18rem;">
        <img class="card-img-top" src="../assets/detajl.jpg" alt="Card image cap">
        <div class="card-body">
          <h5 class="card-title">Leštenie - Renovacia laku</h5>
          <p class="card-text">Nanesenie ochrany na lak vosk, keramika podla dohody</p>
          <div class="d-flex justify-content-between">
            <a  class="btn btn-primary" href="#item-1">Kontaktovat</a>
            <a href="#lestenie" class="btn btn-primary">Viac info</a>
          </div>
        </div>
      </div>
      
      <div class="card m-3 col-2" style="width: 18rem;">
        <img class="card-img-top" src="../assets/svetla.jpg" alt="Card image cap">
        <div class="card-body">
          <h5 class="card-title">lestenie svetlometov</h5>
          <p class="card-text"> Leštenie rotačnou leštičkou do vysokého lesku.
            Zbavenie škrabancov a nedostatkov</p>
            <div class="d-flex justify-content-between">
              <a  class="btn btn-primary" href="#item-1">Kontaktovat</a>
              <a href="#svetla" class="btn btn-primary">Viac info</a>
            </div>
        </div>
      </div>
   
    </div>
  </div>     
</div>
</div>
    
    <div class="neviem"></div>
    <div class="mb-5 container text-center" id="item-1">
      <h6 class="text-center heading">Kontakt</h6>
      <div class="row kontaktik">
        <div class="col d-flex justify-content-center">
          <form action="https://formspree.io/f/xeqwgyla" method="POST">

            <p>Ceny za služby závisia od veľkosti a stavu </p>
            <label>
              Zadajte email:
              <input type="email" name="email">
            </label>
            <label>
              Vyberte si službu:
              <select name="option">
                <option value="option1">Príprava auta na predaj</option>
                <option value="option2">Leštenie auta</option>
                <option value="option3">Interiér</option>
                <option value="option4">Interiér + Lestenie</option>
                
              </select>
            </label>
            <label>
              Zadajte poznámku/otázku:
              <textarea name="message"></textarea>
             </label>
            <!-- your other form fields go here -->
            <button type="submit">Send</button>
          </form>
        </div>

        <div class="col mt-5">
          <div class="card p-5">
              <div class="ig">
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-instagram" viewBox="0 0 16 16">
                  <path d="M8 0C5.829 0 5.556.01 4.703.048 3.85.088 3.269.222 2.76.42a3.917 3.917 0 0 0-1.417.923A3.927 3.927 0 0 0 .42 2.76C.222 3.268.087 3.85.048 4.7.01 5.555 0 5.827 0 8.001c0 2.172.01 2.444.048 3.297.04.852.174 1.433.372 1.942.205.526.478.972.923 1.417.444.445.89.719 1.416.923.51.198 1.09.333 1.942.372C5.555 15.99 5.827 16 8 16s2.444-.01 3.298-.048c.851-.04 1.434-.174 1.943-.372a3.916 3.916 0 0 0 1.416-.923c.445-.445.718-.891.923-1.417.197-.509.332-1.09.372-1.942C15.99 10.445 16 10.173 16 8s-.01-2.445-.048-3.299c-.04-.851-.175-1.433-.372-1.941a3.926 3.926 0 0 0-.923-1.417A3.911 3.911 0 0 0 13.24.42c-.51-.198-1.092-.333-1.943-.372C10.443.01 10.172 0 7.998 0h.003zm-.717 1.442h.718c2.136 0 2.389.007 3.232.046.78.035 1.204.166 1.486.275.373.145.64.319.92.599.28.28.453.546.598.92.11.281.24.705.275 1.485.039.843.047 1.096.047 3.231s-.008 2.389-.047 3.232c-.035.78-.166 1.203-.275 1.485a2.47 2.47 0 0 1-.599.919c-.28.28-.546.453-.92.598-.28.11-.704.24-1.485.276-.843.038-1.096.047-3.232.047s-2.39-.009-3.233-.047c-.78-.036-1.203-.166-1.485-.276a2.478 2.478 0 0 1-.92-.598 2.48 2.48 0 0 1-.6-.92c-.109-.281-.24-.705-.275-1.485-.038-.843-.046-1.096-.046-3.233 0-2.136.008-2.388.046-3.231.036-.78.166-1.204.276-1.486.145-.373.319-.64.599-.92.28-.28.546-.453.92-.598.282-.11.705-.24 1.485-.276.738-.034 1.024-.044 2.515-.045v.002zm4.988 1.328a.96.96 0 1 0 0 1.92.96.96 0 0 0 0-1.92zm-4.27 1.122a4.109 4.109 0 1 0 0 8.217 4.109 4.109 0 0 0 0-8.217zm0 1.441a2.667 2.667 0 1 1 0 5.334 2.667 2.667 0 0 1 0-5.334z"/>
                </svg>
                  <p> bugy_detaling </p>
              </div>
              <div class="email">
          
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-envelope" viewBox="0 0 16 16">
                  <path d="M0 4a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V4Zm2-1a1 1 0 0 0-1 1v.217l7 4.2 7-4.2V4a1 1 0 0 0-1-1H2Zm13 2.383-4.708 2.825L15 11.105V5.383Zm-.034 6.876-5.64-3.471L8 9.583l-1.326-.795-5.64 3.47A1 1 0 0 0 2 13h12a1 1 0 0 0 .966-.741ZM1 11.105l4.708-2.897L1 5.383v5.722Z"/>
                </svg>
                <p>jakubbugal276@gmail.com</p>
              </div>

              <div class="cislo">
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-telephone-fill" viewBox="0 0 16 16">
                  <path fill-rule="evenodd" d="M1.885.511a1.745 1.745 0 0 1 2.61.163L6.29 2.98c.329.423.445.974.315 1.494l-.547 2.19a.678.678 0 0 0 .178.643l2.457 2.457a.678.678 0 0 0 .644.178l2.189-.547a1.745 1.745 0 0 1 1.494.315l2.306 1.794c.829.645.905 1.87.163 2.611l-1.034 1.034c-.74.74-1.846 1.065-2.877.702a18.634 18.634 0 0 1-7.01-4.42 18.634 18.634 0 0 1-4.42-7.009c-.362-1.03-.037-2.137.703-2.877L1.885.511z"/>
                </svg>
                <p>0951381474</p>
              </div>

              <div class="lok">
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-geo-alt" viewBox="0 0 16 16">
                  <path d="M12.166 8.94c-.524 1.062-1.234 2.12-1.96 3.07A31.493 31.493 0 0 1 8 14.58a31.481 31.481 0 0 1-2.206-2.57c-.726-.95-1.436-2.008-1.96-3.07C3.304 7.867 3 6.862 3 6a5 5 0 0 1 10 0c0 .862-.305 1.867-.834 2.94zM8 16s6-5.686 6-10A6 6 0 0 0 2 6c0 4.314 6 10 6 10z"/>
                  <path d="M8 8a2 2 0 1 1 0-4 2 2 0 0 1 0 4zm0 1a3 3 0 1 0 0-6 3 3 0 0 0 0 6z"/>
                </svg>
                <p>Dunajska streda</p>
              </div>

          </div>
        </div>
      </div>
    </div>
 

    
    
    <h2 class=" heading">Podrobne popisané  <span class="bold">Služby</span></h2>
   
    <div class="card info-karty " id="lestenie">
      <img src="../assets/main.png" alt="">
      <h1>Leštenie - Renovacia laku</h1>
      <p>
        Umytie gyon bathe+ šampónom <br>
 Dôkladné vyčistenie podblatníkov a diskov <br> 
 Dekontaminácia od asfaltu, soli a náletovej hrdze <br>
 Opätovné umytie gyon bathe +šampónom <br>
 impregnácia pneumatík <br>
 Vysušenie mikrovláknom <br>
 Viacstupnove leštenie rotačnou leštičkou  <br>
 Na lestenie pouzivame pasty od koch chemie <br>
 Konecne umytie vozidla <br>
 Dekontaminacia laku <br>
 Nanesenie ochrany na lak vosk, keramika podla dohody
      </p>

      <a class="danger">Cena už od 120€</a>
    </div>

    <div class="card info-karty " id="interier">
      <img src="../assets/main.png" alt="">
      <h1>Interiér</h1>
      <p>
         Vyfúkanie prachu zo špár stlačeným vzduchom <br>
         Čistenie medzidverových priestorov <br>
         Kompletné vysávanie interiéru <br>
         Detailné čistenie prístrojovej dosky a dverí <br>
         Čistenie stropu a stĺpikov <br>
         Čistenie špár a medzidverových priestorov <br>
         Čistenie okien z oboch strán <br>
         Dezinfekcia interiéru ozónom 
      </p>

      <a class="danger">Cena už od 70€</a>
    </div>

    <div class="card info-karty " id="svetla">
      <img src="../assets/main.png" alt="">
      <h1>Leštenie svetlometov</h1>
      <p>
         Predumytie aktívnou penou
 Umytie gyon bathe+ autošampónom <br>
 Odhmlenie svetlometov <br>
 Leštenie rotačnou leštičkou do vysokého lesku <br>
 Zbavenie škrabancov a nedostatkov <br>
 Nanesenie ochranného sealantu pred poškodením
      </p>

      <a class="danger">Cena už od 15€ kus</a>
    </div>


    <div class="container" id="foto">
   <h1>Fotogaléria</h1>
      <p>Pre viac fotiek si pozrite náš instagram <span>@bugy_detailing</span></p>
      <div class="row">
        <div class="col-md-4">
          <img src="../assets/main.png" class="img-fluid mt-3"  alt="">
        </div>
        <div class="col-md-4">
          <img src="../assets/main.png" class="img-fluid mt-3"  alt="">
        </div>
        <div class="col-md-4">
          <img src="../assets/main.png" class="img-fluid mt-3"  alt="">
        </div>
      </div>
    </div>

  </div>
</div>
    
  </template>


  <style>
  #foto {
    text-align: center;
  }
  
  .gallery-title {
    font-size: 24px;
    font-weight: bold;
    margin-bottom: 20px;
  }
  
  .gallery-image {
    width: 100%;
    border-radius: 5px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  }

  
  





  @media only screen and (max-width: 600px)  {
    .kontaktik{
      display: flex;
      flex-direction: column;
    }
  }


  span{
    color: black;
  }

  .info-karty{
    
    justify-content: center;
    margin: 10%;
  }

  .navbar{
    border-radius: 0px 0px 30px 30px;
  }

.obr{
 width: -webkit-fill-available ;
}

  p{
    color: 	rgb(152,152,152) ;
  }

.slider{
  margin-top: 200px;

}

.slide{
  border-radius: 100px 100px 0px 0px;
}


*{
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif ;
}

.hr{
  margin-top: 2000px !important;
}


.uvod{
  margin: 50px;
  max-width: 50%;
  border-radius: 50px 0px 50px 0px;

}

.uvodny{
  font-size: 1.2rem;
  line-height: 1.5;
  color: 	rgb(152,152,152);
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 20px;
}

  .comtainer{
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
  }

  .navigacia{
    justify-content: center;
    display: flex;
    width: 70%;
    align-items: center;
  }

.card {
  position: relative;
  overflow: hidden;
}

.card-img-top {
  transition: transform 0.3s;
}

.card:hover .card-img-top {
  transform: scale(1.2);
}


.obr{
  border-radius: 50px 0px 50px 0px;
}

.heading{
  font-size: 3rem;
  margin-top: 200px;
  margin-bottom: 40px;
}


  .container {
    margin-top: 50px;
  }
  
  h1 {
    font-size: 32px;
    color: #333;
    text-transform: uppercase;
  }
  
  .lead {
    font-size: 18px;
    color: #777;
  }
  
  .image-container {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-bottom: 20px;
  }
  
  .image-container img {
    max-width: 100%;
    height: auto;
  }
  
  
  
  .card {
    border: none;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease;
  }
  
  .card:hover {
    transform: scale(1.05);
  }
  
  .list-group-item {
    border: none;
    border-bottom: 1px solid #ddd;
    border-radius: 0;
  }
  
  .list-group-item:last-child {
    border-bottom: none;
  }
  
  .card-text {
    margin-bottom: 10px;
  }
  
  .text-primary {
    color: #007bff;
  }
  
  .text-center {
    text-align: center;
  }
  
  .container button {
    animation: pulse 1s infinite;
  }
  
  @keyframes pulse {
    0% {
      transform: scale(1);
    }
    50% {
      transform: scale(1.1);
    }
    100% {
      transform: scale(1);
    }
  }
  
  .container .image {
    animation: slideIn 1s forwards;
  }
  
  @keyframes slideIn {
    0% {
      opacity: 0;
      transform: translateX(-100%);
    }
    100% {
      opacity: 1;
      transform: translateX(0);
    }
  }
  
  .container .carti .card {
    animation: fadeIn 1s forwards;
  }
  
  @keyframes fadeIn {
    0% {
      opacity: 0;
    }
    100% {
      opacity: 1;
    }
  }
  
  .container form {
    animation: slideUp 1s forwards;
  }
  
  @keyframes slideUp {
    0% {
      opacity: 0;
      transform: translateY(20px);
    }
    100% {
      opacity: 1;
      transform: translateY(0);
    }
  }





  form {
    margin-top: 20px;
    max-width: 400px;
    background-color: #f8f9fa;
    padding: 20px;
    border-radius: 4px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  }
  
  form label {
    display: block;
    margin-bottom: 10px;
    font-weight: bold;
    color: #333;
  }
  
  form input[type="email"],
  form select,
  form textarea {
    width: 100%;
    padding: 10px;
    border-radius: 4px;
    border: 1px solid #ccc;
  }
  
  form textarea {
    height: 100px;
  }
  
  form button[type="submit"] {
    display: block;
    width: 100%;
    padding: 10px;
    margin-top: 20px;
    background-color: #007bff;
    color: #fff;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    transition: background-color 0.3s ease;
  }
  
  form button[type="submit"]:hover {
    background-color: #0056b3;
  }
  
  /* Additional Styles */
  .container {
    margin-top: 50px;
  }
  
  h1 {
    font-size: 32px;
    color: #333;
    text-transform: uppercase;
  }
  
  .lead {
    font-size: 18px;
    color: #777;
  }
  
  .image-container {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-bottom: 20px;
  }
  
  .image-container img {
    max-width: 100%;
    height: auto;
  }
  
  h2 {
    font-size: 24px;
    color: #007bff;
    margin-bottom: 20px;
  }
  
  .card {
    border: none;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease;
  }
  
  .card:hover {
    transform: scale(1.05);
  }
  
  .list-group-item {
    border: none;
    border-bottom: 1px solid #ddd;
    border-radius: 0;
  }
  
  .list-group-item:last-child {
    border-bottom: none;
  }
  
  .card-text {
    margin-bottom: 10px;
  }
  
  .text-primary {
    color: #007bff;
  }
  
  .text-center {
    text-align: center;
  }
  
  .container button {
    animation: pulse 1s infinite;
  }
  
  @keyframes pulse {
    0% {
      transform: scale(1);
    }
    50% {
      transform: scale(1.1);
    }
    100% {
      transform: scale(1);
    }
  }
  
  .container .image {
    animation: slideIn 1s forwards;
  }
  
  @keyframes slideIn {
    0% {
      opacity: 0;
      transform: translateX(-100%);
    }
    100% {
      opacity: 1;
      transform: translateX(0);
    }
  }
  
  .container .carti .card {
    animation: fadeIn 1s forwards;
  }
  
  @keyframes fadeIn {
    0% {
      opacity: 0;
    }
    100% {
      opacity: 1;
    }
  }
  
  .container form {
    animation: slideUp 1s forwards;
  }
  
  @keyframes slideUp {
    0% {
      opacity: 0;
      transform: translateY(20px);
    }
    100% {
      opacity: 1;
      transform: translateY(0);
    }
}

.container form label {
animation: fadeInLeft 1s forwards;
}

@keyframes fadeInLeft {
0% {
opacity: 0;
transform: translateX(-20px);
}
100% {
opacity: 1;
transform: translateX(0);
}
}

.container form input,
.container form select,
.container form textarea {
animation: fadeInRight 1s forwards;
}

@keyframes fadeInRight {
0% {
opacity: 0;
transform: translateX(20px);
}
100% {
opacity: 1;
transform: translateX(0);
}
}

.container form button[type="submit"] {
animation: pulse 1s infinite;
}

</style>
  