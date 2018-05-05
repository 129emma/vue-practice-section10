// this file is for holding each single quote
<template>
  <!-- hold quotes -->
  <div class="col-sm-6 col-md-r col-lg-3">
      <div class="panel panel-default">
          <div class="panel-body quote">
              <slot>
              </slot>    
          </div>
      </div>
  </div>
</template>
<script>
export default {
  
}
</script>
<style>
.panel-body{
    font-family: 'Arizonia',cursive;
    font-size: 24px;
    color: black
}
.quote{
    cursor: pointer;
}
.quote:hover{
    background-color: azure
}
</style>
