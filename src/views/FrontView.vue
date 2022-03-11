<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">前台</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavDropdown">
        <ul class="navbar-nav">
          <li class="nav-item">
            <router-link class="nav-link active" aria-current="page" to="home">Home</router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link" to="productList">產品列表</router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link" to="cartList">購物車列表</router-link>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <router-view />
</template>
