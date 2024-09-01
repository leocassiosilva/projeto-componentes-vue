<template>
    <div>
      <span>Mensagem com múltiplas linhas:</span>
      <p style="white-space: pre-line;">{{ message }}</p>
      <br>
      <textarea v-model="message" placeholder="Escreva bastante"></textarea>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        message: ''  // Inicialize a propriedade message
      }
    }
  }
  </script>
  