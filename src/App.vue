<template>
  <div id="app">
      <!-- <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css"> -->
      <!-- <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
      <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script> -->
    <Header/>
        <h1><strong>Welcome to Best Goat Gifs Ever.biz</strong></h1>
    <GoatGrid/>

  </div>
</template>

<script>
import Header from './components/Header'
import GoatGrid from './components/GoatGrid'
  export default {
     components:{
         'Header':Header,
         'GoatGrid':GoatGrid
     }
  }
</script>

<style>
  *{
      box-sizing:border-box;
      margin:0;
  }
</style>