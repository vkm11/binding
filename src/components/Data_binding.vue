<template>
    <div>
        
        <!-- <h1>{{message}}</h1>
        <input type="text" v-model="message"> -->

         <h1 style="white-space:pre-line">{{message}}</h1>
        <textarea type="text" v-model="message" />
    </div>
</template>
<script>
export default {
  name: 'data-binding',
  data(){
      return{
          message:'Hi'
      }
  }
}
</script>