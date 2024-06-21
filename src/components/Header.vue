<template>
    <header class="header">
      <img src="@/assets/logo.png" alt="Tesla Logo" class="logo">
      <nav class="nav">
        <ul>
          <li><a href="#">Model S</a></li>
          <li><a href="#">Model 3</a></li>
          <li><a href="#">Model X</a></li>
          <li><a href="#">Model Y</a></li>
        </ul>
      </nav>
    </header>
  </template>
  
  <script>
  export default {
    name: 'HeaderComponent'
  }
  </script>
  
  <style>
  .header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
  }
  
  .logo {
    height: 40px;
  }
  
  .nav ul {
    display: flex;
    list-style: none;
  }
  
  .nav li {
    margin: 0 10px;
  }
  
  .nav a {
    text-decoration: none;
    color: #000;
  }
  </style>
  