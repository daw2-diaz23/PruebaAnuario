<template>
  <main>
    <div class="mt-4 container-fluid">
      <a href="./index.html"><button type="button" class="btn btn-dark">VOLVER</button></a> 
    </div>
    <div class="container-fluid d-flex justify-content-center">
      <div class="box ">
        <img src="../imagenes/MESSI.jpg" alt="">
        <div class="info">
          <h2>Messi</h2>
          <p>messi@fpllefia.com</p>
          <div class="d-flex text-center">
            <p>DAW :</p>
            <p class="ms-2">2019-2023</p> 
          </div>  
          <p><i class="fa-sharp fa-solid fa-magnifying-glass"></i></p>     
        </div>
      </div>
    </div>
    <div class="container-fluid d-flex justify-content-center">
      <button type="button" class="btn btn-dark">EDITAR</button>
    </div>
    <div class="accordion mt-4" style="margin-left: 20%; margin-right: 20%;" id="accordionPanelsStayOpenExample">
      <div class="accordion-item ">
        <h2 class="accordion-header" id="panelsStayOpen-headingOne">
          <button class="accordion-button bg-dark text-white" type="button" data-bs-toggle="collapse" data-bs-target="#panelsStayOpen-collapseOne" aria-expanded="true" aria-controls="panelsStayOpen-collapseOne">
            EXPEDIENTE
          </button>
        </h2>
        <div id="panelsStayOpen-collapseOne" class="accordion-collapse collapse show" aria-labelledby="panelsStayOpen-headingOne">
          <div class="accordion-body">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Modi beatae ea explicabo nihil, minima ullam facilis dolore illo quisquam doloremque, labore eligendi magnam quis, sit suscipit expedita libero corporis voluptas.</p>
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Consectetur minus nemo culpa numquam vero dolorum deleniti aut sit corporis dolor repellendus dicta tempora laudantium voluptates voluptatibus itaque est, cum provident!</p>
          </div>
        </div>
      </div>
    </div>
  </main>
</template>