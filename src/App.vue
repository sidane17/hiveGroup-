<script >
import Navbar from './components/Navbar.vue';
export default{
  components:{
    Navbar
  }
};
</script>

<template>
  <Navbar/>
  
    <div class="sezione_uno d-flex justify-content-start align-items-center "> 
      <img src="./assets/Esagoni.png" alt="" width="30%">
      <div class="container d-flex justify-content-center align-items-center ">
         <div class="titol col-7 d-flex justify-content-center align-items-center flex-column">
          <h2 id="font"><b>Conetti.</b></h2>
          <h2 id="font"><b>Crea.</b></h2>
          <h2 id="font"><b>Sorprendi.</b></h2>
         </div>
        <div class="titol  col-5">
          <div> </div>
        </div>
      </div>
   
    </div>
    <div class="sezione_due ">

    </div>
 
  
</template>

<style >

.sezione_uno{
  width: 100%;
  height: 55vh;
  position: relative;
  z-index: 0;
  overflow-y: hidden;
  background: linear-gradient(to bottom, white, antiquewhite); /* Gradiente dal bianco all'antique white */
  overflow: hidden;
   border-style: dashed;

}
.im{
  position: relative;
}
.titol{
  border-style: dashed;
  height: 30rem;
}
#font{
  font-size: 6rem;
  color: rgb(226, 148, 30);
}
.sezione_due{
  width: 100%;
  height: 100vh;
  border-style: dashed;
  background-color: antiquewhite;
}
.sezione_uno > img {
  position: absolute;
 top: 20px;
 right: -100px;
  transform: rotate(40deg); /* Ruota di 45 gradi */
  transition: transform 0.5s; /* Transizione fluida */
  z-index: 99;
}
</style>
