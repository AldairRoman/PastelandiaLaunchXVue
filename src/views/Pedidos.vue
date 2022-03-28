<template>
    <Nav/>
    <div>
        <h2 class="textCenter">Aquí puedes hacer tu pedido</h2>
    </div>
    <Formulario/>
</template>

<script>
import Nav from '../components/Nav.vue'
import Formulario from '../components/Formulario.vue'
export default {
    name:'PedidosView',
    components:{
     Nav,
     Formulario
    }
}
</script>