<template>
   <!-- <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav> -->
  <router-view/>
</template>

<style>
*{
    font-family: 'Pacifico',sans-serif, cursive;
 }

 nav
 {
  background:  linear-gradient(to right, rgb(206, 123, 209), rgb(255, 255, 255));
  display: flex;
  justify-content: flex-end; 
  border: 5px;
  border-color: black;
  border-style: solid;
}

.footer
{
 
  margin: 15px 0px 0px 0px;
  display: flex;
  justify-content: space-around;
  
}

button
{
   width: 150px;
   margin-top: none;
   background:  linear-gradient(to right, rgb(206, 123, 209), rgb(255, 255, 255));
   border: 5px;
   border-color: black;
   border-style: solid;
 
}

#txtDescripcion
{
   width : 500px;
   height: 200px;
}

.p-nav
{
   position: absolute;
   left: 100px;
   top: -5px;
   padding: 2.5px;
   font-size: 25px;
}
.img-nav
{

   width: 80px;
   position: absolute;
   left: 10px;
   top: 0px;
   padding: 5px;

}
.nav-a{
 display: inline-block;
 font-size: 20px;
 padding: 15px;
 color: black;
 text-decoration: none;
}

.nav-a:hover
{
   color: white;
}

.imgSabores
{
   width: 150px;
}
.cointainer
{
  margin: 0 auto;
  width: 80%;
  display: flex;
  flex-wrap: wrap;

}
.sabores-columna
{
   border: 5px;
   background:  linear-gradient(to right, rgb(206, 123, 209), rgb(255, 255, 255)); 
   border-color: #000000;
   border-style: solid;
   margin: 0px auto;
   padding: 10px;
   border-radius: 10%;
   box-shadow: -10px -10px 5px #999999;
   width: 20%;
   box-sizing: border-box;
}
.textCenter
{
   text-align: center;
}


.datosUsuario
{
   display: flex;
   flex-wrap: wrap;  
   justify-content: center;
   border: 5px;
   border-color: #000000;
   border-radius: 15px;
   border-style: solid;
   background:  linear-gradient(to right, rgb(206, 123, 209), rgb(255, 255, 255));

}

.basicdata
{
   width: 600px;
   height: 520px;
   margin: 15px;
}

.seleccionSabor
{
  width: 500px;
  height: 500px;
  margin-top: 30px;
  margin-left: 10px;
  text-align: center;
   
}

.lblTituloSabor
{
   margin: 35px;
}

.lblSabor
{
   margin-left: 15px;
}



.imagen-pedido
{
   width:200px;
   margin-top: 50px; 
}

table {
   border-collapse: collapse;
   width: 50%;
   margin-left: auto;
   margin-right: auto;
   text-align: left; 
 }

 .table-contacto {
   border-collapse: collapse;
   width: 70%;
   margin-left: auto;
   margin-right: auto;
   text-align: left; 
 }



 td, th {
   border: 1px solid #070707;
   text-align: left;
   padding: 8px;
 }
 
 tr:nth-child(even) {
   background-color: rgb(206, 123, 209);
 }

 .txtTable{
    font-size: 20px;
 }





@media (max-width:1500px) {
   .datosUsuario
{
   display: flex;
   flex-wrap: wrap;  
   justify-content: center;
   border: 5px;
   border-color: #000000;
   border-radius: 15px;
   border-style: solid;
   background:  linear-gradient(to right, rgb(206, 123, 209), rgb(255, 255, 255));

}
   .sabores-columna
   {
      width: 45%;
      margin-bottom: 30px;
   }
   .p-nav
   {
      display: none;
   }
}

@media (max-width:600px) {
   .sabores-columna
   {
      width: 45%;
      margin-bottom: 30px;
   }
   .p-nav
   {
      display: none;
   }

   #txtDescripcion
   {
     width : 300px;
     height: 200px;
   }
}


@media (max-width:500px) {
   .sabores-columna
   {
      width: 100%;
      margin-bottom: 30px;
   }
   .p-nav
   {
      display: none;
   }
   .img-nav
   {
      display: none;
   }
}
</style>
