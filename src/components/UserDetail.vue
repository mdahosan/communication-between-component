<template>
  <div class="component">
    <h3>You may view the user details here</h3>
    <p>Details</p>
    <p>User Name: {{ myName }}</p>
  </div>
</template>

<!--props name is same as what we using on template. because behind the seen this will create the property-->

<script>
    export default {
      props: ['myName']
    }
</script>

<style scoped>
  div{
    background-color: lightcoral;
  }
</style>
