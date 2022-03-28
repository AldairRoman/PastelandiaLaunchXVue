<template>
<Nav/>
  <!--Sabores-->
    <div>
        <h2 class="textCenter">Sabores</h2>
    </div>
      <Sabores/>
     <!-- Adornos -->
    <div>
        <h2 class="textCenter">Adornos</h2>
    </div>
    <Adornos/>
    <InfoPasteleria/>

</template>


<script>
// @ is an alias to /src
import Nav from '@/components/Nav.vue'
import Sabores from '@/components/Sabores.vue'
import Adornos from '@/components/Adornos.vue'
import InfoPasteleria from '@/components/InfoPasteleria.vue'

export default {
  name: 'HomeView',
  components: {
    Nav,
    Sabores,
    Adornos,
    InfoPasteleria
  }
}
</script>
