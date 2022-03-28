<template>
  
  <Nav/>
  <!--Inventario de sabores-->
            <h3 class="textCenter">Inventario de sabores</h3>
             <InfoCantidadSabores/>
  <!--Inventario de adornos-->
             <h3 class="textCenter">Inventario de Adornos</h3>
             <InventarioAdornos/>
  <!-- Pedidos Nuevos -->
         <h3 class="textCenter">Pedidos Nuevos</h3>
         <PedidosNuevos/>

</template>
<script>
import Nav from '../components/Nav.vue'
import InfoCantidadSabores from '../components/InfoCantidadSabores.vue'
import InventarioAdornos from '../components/InfoCantidadAdorno.vue'
import PedidosNuevos from '../components/PedidosNuevos.vue'
export default {
  name:'Admin-Pasteleria',
  components:{
    Nav,
    InfoCantidadSabores,
    InventarioAdornos,
    PedidosNuevos
  }

}
</script>
