<template>
  <div>
    <h2>
      {{ msg }}
    </h2>
      
  </div>
</template>
<script>
export default {
  data(){
    return {
      msg:'Hello github'
    }
  },
  // async created(){
  //   const result = await axios({
  //     url: 'http://localhost:8080/hello',
  //     method:'GET'
  //   })
  //   this.msg = result.data.obj.msg
  // }
}
</script>