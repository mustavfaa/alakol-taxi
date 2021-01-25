
<template>
  <div>
    <navbar/>
    <div  style="margin-top: 46px;">
    	<nuxt />	
    </div>
    <fooDer />
      
  </div>
</template>

<script>
import navbar from '@/components/navbar'
import fooDer from '@/components/fooDer'
export default {
  components: {
    navbar,
    fooDer
  }
}
</script>


<style>
body{
   
}
</style>