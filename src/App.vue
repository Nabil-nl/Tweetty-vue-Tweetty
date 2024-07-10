<template>
    <div id="app">
      <HelloWorld />
      <Section />
      <Right />
    </div>
  </template>
  
  <script>
  import HelloWorld from './components/HelloWorld.vue';
  import Section from './components/Section.vue';
  import Right from './components/Right.vue';
  
  export default {
    name: 'App',
    components: {
      HelloWorld,
      Section,
      Right
    }
  };
  </script>
  
  <style>
  
  </style>
  