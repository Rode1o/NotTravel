<template>
<v-container class="d-flex flex-row flex-wrap m-6">
  
  <Card username="Guillermo Paez Guerra" urlimg="../assets/GLL.jpg" description="Front-End developer"/>
  <Card username="Wilson Andres Carvajal Barreto" urlimg="../assaets/AC.jpeg" description="Front-End developer"/>
  <Card username="Duvan Rodelo" urlimg="../assets/DUVAN.jpeg" description="Front-End developer"/>
  <Card username="Diego Rojas Avellaneda" urlimg="../assets/DG.jpg" description="Front-End developer"/>
  <Card username="Manuel Alejandro Rativa Rodriguez" urlimg="@/assets/Manuel.jpeg" description="Front-End developer"/>
</v-container>
</template>

<script>
import Card from "../components/Card.vue";
 
export default {
 components: {
   Card
 }
}
</script>