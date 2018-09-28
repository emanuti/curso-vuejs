<template>
  <div id="app">
    <img src="./assets/logo.png">
    {{ msg }}
    <ul>
      <li v-for="numero of numeros">
        {{ numero.numero }} - {{ numero.dsNumero }}
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Bem vindo ao Vue.js App',
      numeros: [
        { numero: 1,  dsNumero: 'Um'     },
        { numero: 2,  dsNumero: 'Dois'   },
        { numero: 3,  dsNumero: 'Três'   },
        { numero: 4,  dsNumero: 'Quatro' },
        { numero: 5,  dsNumero: 'Cinco'  },
        { numero: 6,  dsNumero: 'Seis'   },
        { numero: 7,  dsNumero: 'Sete'   },
        { numero: 8,  dsNumero: 'Oito'   },
        { numero: 9,  dsNumero: 'Nove'   },
        { numero: 10, dsNumero: 'Dez'    }
      ]
    }
  }
}
</script>

<style>

</style>
