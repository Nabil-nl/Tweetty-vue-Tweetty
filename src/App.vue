<template>
    <div id="app">
      <HelloWorld />
      <Section />
    </div>
  </template>
  
  <script>
  import HelloWorld from './components/HelloWorld.vue';
  import Section from './components/Section.vue';
  
  export default {
    name: 'App',
    components: {
      HelloWorld,
      Section 
    }
  };
  </script>
  
  <style>
  
  </style>
  