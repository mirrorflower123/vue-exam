<template>
    <div>{{ title }}</div>
  </template>
  
  <script>
  let app
  export default {
    name: 'Hello World',
    data() {
      return {
        title: 'Hello World',
      }
    },
    computed: {},
    methods: {},
    created() {
      app = this
      console.log(app.title)
    },
  }
  </script>