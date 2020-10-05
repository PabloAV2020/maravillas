<template>
    <div class="hello">
      <div class="menu">
          <div class="menu-item">
            <div class="menu-text">
                Servicios
            </div>
          </div>
         <div class="menu-item">
           <div class="menu-text">
              Galería
           </div>
         </div>
          <div class="menu-item-menu-center">
            <img src="../assets/img/centerlogow.svg" alt="Logo" >
          </div>
         <div class="menu-item">
           <div class="menu-text">
             Acceso
           </div>
        </div>
         <div class="menu-item">
           <div class="menu-text">
             Contacto
            </div>
        </div>
      </div>
      <div class="responsive">
        <img src="../assets/img/2.png" alt="Banner" >
      </div>
      <div class="bienvenida">
        <h2>
          ! Bienvenido a nuestra página !
          <br>
          <h3>
            Te esperamos en el sur del sur, la hermosa e indomable Patagonia, lugar lleno de maravillas de la naturaleza. 
          </h3>
        </h2>
      </div>
    </div>

</template>

<script>


export default {
  name: 'Home',
  props: {
    msg: String
  }


}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello{
  align-items: center;
  justify-content: space-around;
}

.menu {
  display: flex;
  align-items: center;
  justify-content: space-around;
  margin-top: 10px;
  height: 60px;
}

.menu-item{
  flex: 1;
  text-align: center;
  display: flex;
  justify-content: center;
  align-items: center;
}

.menu-text{
  margin-top:30px;
  font-size: 20px;
  color: white;
  font-weight: bold;
  cursor: pointer;
  padding: 10px;
  border-bottom: 2px solid #080808;
  width: fit-content;
}

.responsive img{
  margin-top: 55px;
  width: 100%;
  height: auto;
  border: 2px solid black;
}

.menu-item-menu-center img{
  margin-top:80px;
  width: 120px;
  height: 120px;
  margin-bottom: 20px;
}

.menu-text:hover {
  border-bottom: 2px solid white;
}

.bienvenida h2{
  font-family: Arial, Helvetica, sans-serif;
  font-size: 12pt;
  font-weight: bold;
}

.bienvenida h3{
  font-family: Arial, Helvetica, sans-serif;
  font-size: 10pt;
}






</style>
