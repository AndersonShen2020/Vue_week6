<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-secondary">
    <div class="container">
      <a class="navbar-brand" href="#">Coffee 專賣店</a>
      <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <router-link class="nav-link" to="/about"> 簡介 </router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link" to="/products"> 產品 </router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link" to="/Cart">
              <i class="bi bi-cart"></i>
            </router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link" to="/Login">
              <i class="bi bi-person-circle"></i>
            </router-link>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<style lang="scss">
.nav-item {
  padding: 5px;
}
</style>
