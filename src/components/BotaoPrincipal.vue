<script lang="ts">
export default {
   methods: {
      aoClicar() {
         window.alert('Botão sem função... somente visual')
      }
   },
}
</script>

<template>
   <div class="buscar">
      <button @click="aoClicar()">
         Buscar receitas!
      </button>
   </div>
</template>

<style scoped>
   .buscar {
      width: 100%;
      display: flex;
      height: 40px;
      padding: 20px 0px 110px 0px;
      justify-content: center;
      align-items: center;
      background-color: white;
   }

   .buscar > button {
      color: white;
      background-color: #EA5127;
      border-radius: 30px;
      width: 240px;
      height: 60px;
      font-size: 20px;
      font-weight: 600;
   }

   button:hover {
      background-color: #521707;
   }
</style>