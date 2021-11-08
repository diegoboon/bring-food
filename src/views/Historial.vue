<template>
  <div class="home">
    <div class="header">
      <img class="logo" src="../assets/img/logo2.png">
      <h2 class="title"><b>Historial</b> de pedidos...</h2>
      <div class="input">
        <input type="text" placeholder="¿Deseas buscar?... " />
        <div class="icon-input">
          <i class="bx bx-search"></i>
        </div>
      </div>
      
      
    </div>

    <div class="container mt-5 mb-3">
    <div class="row">
        <div class="col-md-4">
            <div class="card p-3 mb-2">
                <div class="d-flex justify-content-between">
                    <div class="d-flex flex-row align-items-center">
                        <div class="icon">  <img style="width:100%;" src="../assets/img/doritos.png">  </div>
                        <div class="ms-2 c-details">
                            <h6 class="mb-0">Doritos</h6> <span>11:00 am</span>
                        </div>
                    </div>
                    <div  class="badge"> <span>Pendiente</span> </div>
                </div>
                <div class="mt-5">
                        <div class="progress ">
                            <div class="progress-bar" role="progressbar" style="width: 10%" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100"></div>
                        </div>
                        <div class="mt-3"> <span class="text1">10 min <span class="text2">para la entrega</span></span> </div>
                    </div>
               
            </div>
        </div>

        <div  class="col-md-4">
            <div  class="card p-3 mb-2">
                <div class="d-flex justify-content-between">
                    <div class="d-flex flex-row align-items-center">
                        <div class="icon">  <img style="width:100%;" src="../assets/img/cocacola.png">  </div>
                        <div class="ms-2 c-details">
                            <h6 class="mb-0">CocaCola</h6> <span>11:00 am</span>
                        </div>
                    </div>
                    <div  class="badge"> <span>Pendiente</span> </div>
                </div>
                <div class="mt-5">
                        <div class="progress">
                            <div class="progress-bar" role="progressbar" style="width: 40%" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100"></div>
                        </div>
                        <div class="mt-3"> <span class="text1">7 min <span class="text2">para la entrega</span></span> </div>
                    </div>
               
            </div>
        </div>

        <div  class="col-md-4">
            <div  class="card p-3 mb-2">
                <div class="d-flex justify-content-between">
                    <div class="d-flex flex-row align-items-center">
                        <div class="icon">  <img style="width:100%;" src="../assets/img/rufflesoriginal.png">  </div>
                        <div class="ms-2 c-details">
                            <h6 class="mb-0">CocaCola</h6> <span>11:00 am</span>
                        </div>
                    </div>
                    <div  class="greene"> <span>Entregado</span> </div>
                </div>
                <div class="mt-5">
                        <div class="progress">
                            <div class="progress-bar" role="progressbar" style="width: 100%" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100"></div>
                        </div>
                        <div class="mt-3"> <span class="text1">0 min <span class="text2">para la entrega</span></span> </div>
                    </div>
               
            </div>
        </div>
        
        
    </div>
</div>
    
  </div>
</template>


