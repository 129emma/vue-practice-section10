// this file for adding new quote
<template>
  <!-- hold quotes -->
  <div class="row">
      <app-quote v-for="quote in quotes">
          {{ quote }}
      </app-quote>    
  </div>
</template>
<script>

export default {
  components:{
      appQuote: Quote
  }
}
</script>
<style>

</style>