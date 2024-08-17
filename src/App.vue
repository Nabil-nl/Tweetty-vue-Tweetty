<template>
    <div id="app">
      <Sidebar />
      <Section />
      <Right />
    </div>
  </template>
  
  <script>
  import Sidebar from './components/Sidebar.vue';
  import Section from './components/Section.vue';
  import Right from './components/Right.vue';
  
  export default {
    name: 'App',
    components: {
      Sidebar,
      Section,
      Right
    }
  };
  </script>
  
  <style>
  
  </style>
  