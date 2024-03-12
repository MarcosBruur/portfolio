<script>
import {ref,onBeforeMount} from 'vue'
import config from './components/token.js'

export default{
  components:{

  },
  setup(){
    let token = config.token

    return{
      token,
    }
  }
  
}

</script>

<template>
  
</template>

<style></style>

