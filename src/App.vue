<template>
  <div>导航栏 | <router-link to="/">Demo</router-link> | <router-link to="/2">
  Demo2</router-link></div>
  <hr/>
  <router-view />
</template>

<script>

export default {
  name: 'App'
}
</script>
