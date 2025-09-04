<template>
  <div>
    <h1>Welcome to the homepage</h1>
    <AppAlert>
      This is an auto-imported component aaaxxxxxxxxxxxxxxx
    </AppAlert>
    <div>
      <Child :nama="namaUser" />
    </div>
  </div>
</template>

<script setup>
import { onMounted } from 'vue' // Vue Composition API

const namaUser = 'hadi'

const consoleMe = () => {
  console.log("wow")
}

onMounted(() => {
  consoleMe()
})
</script>