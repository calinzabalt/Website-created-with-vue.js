<template>
  <section class="container">

    <div class="intro">
      <div class="overlay">
      <h1>Vând lemne de foc</h1>
     
    </div>
  </div>

  <div class="info">
    <div class="info1">
    <p>"TIM LAUVA" este o companie care pune la dispoziția dumneavoastră lemne de foc.
Comercializarea lemnelor de foc se face în toată țara (transportul fiind gratis doar în județul Arad)<br>
Timp de livrare: 24h. <br>
Pentru mai multe detalii sunați la numărul afișat: 0757 303 788</p>

      </div>  
    </div>
    
  </section>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    
  }
}
</script>

<style scoped>
.intro {
      background:url('../images/rise-1789903_1920.jpg') left bottom no-repeat fixed;
      height:800px;width:100%;
    }

    h1 {
      margin:0;
      color:#fff;
      font-size:75px;
      text-align:center;
      font-family: times;
    }

    h3 {
      text-align:center;
      color:#fff;
      font-size:30px;
      font-weight:300;
    }

    h4 {
      font-size:25px;
      font-weight:300;
      color:#fff;
      text-align:center;
    }
    
    .overlay {
      background-color:rgba(0, 0, 0, 0.5);width:100%;height:100%;display:flex;flex-flow:column wrap;align-items:center;justify-content:center;
    }

    .info {
      display: flex;
      flex-flow: row wrap;
      align-items: center;
      justify-content: center;
      padding-top: 60px;
      padding-bottom: 60px;
      text-align: center;
         
    }

    .info1 {
    box-sizing: border-box;
    width: 800px;
    padding: 8px;
    border: 1px solid #ccc;
    box-shadow: 0 2px 2px #aaa;
         
    }    

    p {
      font: times;
      font-weight:500;
      font-size: 23px;
    }
    
</style>
