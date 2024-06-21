<template>
    <section class="section" :style="{ backgroundImage: 'url(' + backgroundImage + ')' }">
      <div class="content">
        <h1>{{ title }}</h1>
        <p>{{ description }}</p>
      </div>
    </section>
  </template>
  
  <script>
  export default {
    name: 'SectionComponent',
    props: {
      title: String,
      description: String,
      backgroundImage: String
    }
  }
  </script>
  
  <style>
  .section {
    height: 100vh;
    background-size: cover;
    background-position: center;
    display: flex;
    align-items: center;
    justify-content: center;
    color: white;
    text-align: center;
  }
  
  .content {
    background: rgba(0, 0, 0, 0.5);
    padding: 20px;
    border-radius: 10px;
  }
  </style>
  