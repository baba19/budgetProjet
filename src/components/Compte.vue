<template>
<div class='main'>
    <p>hello</p>
    <b-table  bordered outlined hover small :items="items"></b-table>
</div>       
</template>
<script>
import 'bootstrap/dist/css/bootstrap.css'
import 'bootstrap-vue/dist/bootstrap-vue.css'
export default {
   name:'Compte',
   data() {
       return{
           items:[
               {
                date: '2018-07-22',
                libelle: 'sandwich',
                prix: '5'
               },
                {
                date: '2018-07-22',
                libelle: 'céréales',
                prix: '3'
               }
            ]
       }
       
   }
}
</script>
<style>
.main{
    margin-left: 5em;
    margin-right:5em;
}
</style>


