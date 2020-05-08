
<template>
<div>
<h1>Login</h1>

<div>
<label>mobile no</label>
<Input/>
</div>

  <div>OTP <Input/></div>

  <button>Login</button>
</div>



</template>



<script>
import Input from '../common/Input.vue'

export default {
  name: 'Login',
  components:{
    Input
  }
}   
</script>
