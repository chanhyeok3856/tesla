<template>
    <main>
      <Section
        v-for="(section, index) in sections"
        :key="index"
        :title="section.title"
        :description="section.description"
        :backgroundImage="section.backgroundImage"
      />
    </main>
  </template>
  
  <script>
  import Section from './Section.vue';
  
  export default {
    name: 'MainContentComponent',
    components: {
      Section
    },
    data() {
      return {
        sections: [
          {
            title: 'Model S',
            description: 'Order Online for Touchless Delivery',
            backgroundImage: 'path/to/model-s.jpg'
          },
          {
            title: 'Model 3',
            description: 'Order Online for Touchless Delivery',
            backgroundImage: 'path/to/model-3.jpg'
          },
          {
            title: 'Model X',
            description: 'Order Online for Touchless Delivery',
            backgroundImage: 'path/to/model-x.jpg'
          },
          {
            title: 'Model Y',
            description: 'Order Online for Touchless Delivery',
            backgroundImage: 'path/to/model-y.jpg'
          }
        ]
      };
    }
  }
  </script>
  
  <style>
  main {
    overflow: hidden;
  }
  </style>
  