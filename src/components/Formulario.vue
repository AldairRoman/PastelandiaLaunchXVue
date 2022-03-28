<template>
    <div class="datosUsuario">
       <div class="basicdata">
               <ul>
               <li>
                <label for="txtNombre">Nombre</label>
                <br>
                 <input type="text" id="txtNombre" name="txtNombre">
              </li> 
              <li>
                <label for="txtTel">Telefono</label>
                <br>
                <input type="tel" id="txtTel" name="txtTel" maxlength="10">
              </li> 
              <li>
                <label for="txtMail">Correo electronico</label>
                <br>
                <input type="email" id="txtMail" name="txtMail">
              </li> 
              <li>
                <label for="txtDescripcion">Cuentanos acerca de tu pastel</label>
                <br>
                <input type="text" id="txtDescripcion" name="txtDescripcion">
             </li> 
             
            </ul>
       </div>
       <div class="seleccionSabor">
           <label class="lblTituloSabor">Selecciona los sabores de tu pastel</label><br>
           <label><input class="lblSabor" type="checkbox" id="cboxv" value="vainilla"> vainilla</label>
           <label><input class="lblSabor" type="checkbox" id="cboxch" value="chocolate"> chocolate</label>
           <label><input class="lblSabor" type="checkbox" id="cboxf" value="fresa">fresa</label>
           <label><input class="lblSabor" type="checkbox" id="cboxc" value="coco">coco</label><br>
           <br>
           <label>Selecciona los adornos para el pastel</label><br>
           <label><input class="lblSabor"  type="checkbox" id="cboxb" value="boda">boda</label>
           <label><input class="lblSabor"  type="checkbox" id="cboxf" value="felicitaciones">felicitaciones</label>
           <label><input class="lblSabor"  type="checkbox" id="cboi" value="infantiles">infantiles</label>
           <label><input class="lblSabor"  type="checkbox" id="cboxp" value="personalizado">personalizado</label>
           <img class="imagen-pedido" src="../assets/Img/Logo.png" alt="imagen-logo">
           <br>
           <button>Enviar</button>
        </div>   
    </div>
</template>

<script>
export default {
    name:'Formulario-Clientes'
}
</script>