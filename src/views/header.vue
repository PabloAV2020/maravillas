<template>
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
</template>

<script>

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

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
  font-size: 18px;
  color: white;
  font-weight: bold;
  cursor: pointer;
  padding: 10px;
  border-bottom: 2px solid #080808;
  width: fit-content;
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


</style>
