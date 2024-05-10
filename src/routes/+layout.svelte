<script lang="ts">

  </script>
 <!-- App.svelte -->
<nav class="navbar">
    <div class="left-section">
      <a href="/inicio">Inicio</a>
      <a href="/servicios">Servicios</a>
      <a href="/precios">Precios</a>
    </div>
    <div class="right-section">
        <a href="/login">Iniciar sesion</a>
        <a href="/register">Registrarse</a>
    </div>
  </nav>
  <slot />
  <div>
    <p>hola</p>
  </div>
  <style>
    .navbar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 10px 20px;
      background-color: #333;
      color: #fff;
    }
  
    .left-section,
    .right-section {
      display: flex;
      align-items: center;
    }
  
    .left-section a,
    .right-section a {
      color: #fff;
      text-decoration: none;
      margin: 0 10px;
    }
  
    .right-section img {
      width: 40px;
      height: 40px;
      border-radius: 50%;
      object-fit: cover;
      margin-right: 10px;
    }
  </style>