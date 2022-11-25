<template>
 <div>
   <b-container>
   
     <TopHeader/>
	 <SignIn/>
	 <Foot/>
   </b-container> 
  </div> 
</template>
<script>

import TopHeader from './TopHeader.vue'
import Foot from './Foot.vue'
import SignIn from './SignIn.vue'

export default {
  name: 'Prefer',
  
  components : {
  
  Foot,
  TopHeader,
  SignIn
  
  }
}
</script>