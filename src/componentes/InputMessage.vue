<template>
    <input v-model="message" placeholder="Edite-me">
    <p>A mensagem é: {{ message }}</p>
  </template>
  
  <script>
  export default {
    data() {
      return {
        message: ''  // Defina a propriedade message como uma string vazia
      }
    }
  }
  </script>
  