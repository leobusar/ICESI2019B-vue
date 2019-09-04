<template>
  <div>
      {{ mensaje }}
  </div>
</template>

<script>
export default {
    props: ['mensaje'],
    data()  {
        return {       
            mess: this.mensaje
        }
    }
}
</script>

<style>

</style>