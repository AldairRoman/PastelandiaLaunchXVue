<template>
     <Section class="section-nav">
        <nav>
            <p class="p-nav">Pastelandia LaunchX</p>
            <img class="img-nav " src="../assets/Img/Logo.png" alt="Logo-imagen">
            <router-link class="nav-a" to="/">Inicio</router-link>
            <router-link class="nav-a" to="/pedidos">Pedidos</router-link>
             <router-link class="nav-a" to="/admin">Administración</router-link>
        </nav>
    </Section>
</template>
<script>
 export default {
  name:'Nav-Pastel'
}
</script>
