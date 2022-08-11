<template>
  <div>

    <p className="message">
        {{message}}
    </p>

    </div>
</template>
    
<script>
export default {
    name: "message",
    props:{
        message:String,
    }

}
</script>

<style>
</style>