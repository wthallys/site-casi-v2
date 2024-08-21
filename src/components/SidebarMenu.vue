<template>
    <aside class="sidebar">
        <div class="logo">
            <img src="@/assets/logo_casi.png" alt="CASI ADA" width="90" height="90">
            <div class="logo-name">
                <h2>CASI ADA</h2>
                <p>Centro Acadêmico de Sistemas de Informação</p>
            </div>
        </div>
        <nav>
            <RouterLink to="/" class="menu-item">
                <img src="@/assets/tramite-300.png" alt="Manual do Calouro" class="icon">
                <span>Manual do Calouro</span>
            </RouterLink>
        </nav>
    </aside>
</template>

<style>
.sidebar {
    width: 300px;
    height: 100vh;
    background-color: #f3f4f6;
    padding: 10px;
    display: flex;
    flex-direction: column;
    align-items: center;
    margin: 0px;
}

.sidebar nav {
    margin-top: 20px;
    width: 100%;
}

.logo {
    display: flex;
    flex-direction: row;
}

.menu-item {
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 10px;
  border-radius: 8px;
  text-decoration: none;
  color: #000;
  transition: background-color 0.3s ease;
}

.menu-item:hover {
  background-color: #e0e0e0;
}

.icon {
  width: 20px;
  margin-right: 10px;
}

.logo-name {
    font-family: "Roboto Slab", serif;
}

</style>