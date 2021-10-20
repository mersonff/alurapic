<template>
  <div>
    <h1>{{ titulo }}</h1>

    <ul>
      <li v-for="foto of fotos">
        <img :src="foto.url" :alt="foto.titulo">
      </li>
    </ul>
    
    
  </div>
</template>

<script>
export default {

  data(){
    
    return {

      titulo: 'Alurapic',
      fotos: [
        {
          url: 'https://www.petz.com.br/blog/wp-content/uploads/2021/03/piercing-para-cachorro-2.jpg',
          titulo: 'cachorro'
        },
        {
          url: 'https://www.petz.com.br/blog/wp-content/uploads/2021/03/piercing-para-cachorro-2.jpg',
          titulo: 'cachorro'
        }
      ]
    }
  }
 
}
</script>

<style lang="scss">
</style>
