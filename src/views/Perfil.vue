<template>
  <div class="home">
    <div class="header">
      <img class="logo" src="../assets/img/logo2.png">
      
      <div class="container mt-4">
    <div class=" p-3">
        <div >
            <div >
                <div> 
                    <div class="d-flex flex-row mt-3"> <img src="https://i.imgur.com/rvQ3LAt.jpg" width="30%" class="rounded-circle">
                        <div class="ms-2 d-flex flex-column">
                            <div class="d-flex flex-row align-items-center">
                                <strong><h1>Diego Moreno</h1></strong> <span class="dots"></span>
                            </div> <span class="days-ago">4to LCD</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    
    
</div>

<div style=" width:100%; border-radius:100px;" class="btn-group-vertical">
    
   <button type="button" style="background-color:#ff8647; color:#fff; font-weight:bold;" class="btn "><i style="float:left; " class="bx bx-user-circle"></i>Perfil</button>
    <button type="button" style="background-color:#ff8647; color:#fff; font-weight:bold;" class="btn "><i style="float:left;"  class="bx bx-message-rounded-dots"></i>Mensajes</button>
    <button type="button" style="background-color:#ff8647; color:#fff; font-weight:bold;" class="btn "><i style="float:left;"  class="bx bx-message-square-edit"></i>Pedidos</button>
    <button type="button" style="background-color:#ff8647; color:#fff; font-weight:bold;" class="btn "><i style="float:left;"  class="bx bx-coin"></i>PoliCoins</button>
    <button type="button" style="background-color:#ff8647; color:#fff; font-weight:bold;" class="btn "><i style="float:left;"  class="bx bx-mobile-vibration"></i>Configuracion</button>
</div>
      
<!-- Button trigger modal -->
<button  type="button" style="background-color:#86c846; color:#fff; width:100%;" class="btn" data-bs-toggle="modal" data-bs-target="#exampleModal">
  Salir
</button>

<!-- Modal -->
<div  class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div  class="modal-dialog">
    <div style="background-color:#86c846;" class="modal-content">
      <div class="modal-header">
        <h5 style="color:#fff; font-weight:bold;" class="modal-title" id="exampleModalLabel">Salir</h5>
        <button type="button" class="btn-close"  data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div style="color:#fff;" class="modal-body">
        Está seguro que desea cerrar su sesión en Bring Food
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-danger" data-bs-dismiss="modal">No</button>
        <button type="button" class="btn btn-success">Si</button>
      </div>
    </div>
  </div>
</div>
      
    </div>
    
    
    

    
    
  </div>
</template>


