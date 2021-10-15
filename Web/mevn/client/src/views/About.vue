<template>
<v-container class="d-flex flex-row flex-wrap m-6">
  <Card username="Guillermo Paez Guerra" urlimg="https://i.ibb.co/KLfK37B/GLL.jpg" description="Front-End developer"/>
  <Card username="Wilson Andres Carvajal Barreto" urlimg="https://i.ibb.co/jb8F3xP/AC.jpg" description="Front-End developer"/>
  <Card username="Duvan Rodelo" urlimg="https://i.ibb.co/PrNWrFK/DUVAN.jpg" description="Front-End developer"/>
  <Card username="Diego Rojas Avellaneda" urlimg="https://i.ibb.co/FqLtLJv/DG.jpg" description="Front-End developer"/>
  <Card username="Manuel Alejandro Rativa Rodriguez" urlimg="https://i.ibb.co/ZBWbmpF/Manuel.jpg" description="Front-End developer"/>
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
