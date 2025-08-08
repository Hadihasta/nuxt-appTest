<template>
  <div>
    <h1>Welcome to the homepage</h1>
    <AppAlert> This is an auto-imported component aaaxxxxxxxxxxxxxxx </AppAlert>
    <div>
      <Child :nama="namaUser" />
    </div>
  </div>
</template>


<script setup>

const namaUser = 'hadi'
</script>