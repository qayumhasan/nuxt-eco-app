<template>
    
    <nav
      class="navbar navbar-expand-lg navbar-light osahan-menu-2 pad-none-mobile"
    >
      <div class="container">
        <div class="collapse navbar-collapse" id="navbarText">
          <ul class="navbar-nav ml-auto mt-2 mt-lg-0">
            <li class="nav-item">
              <a class="nav-link shop" href="index.html"
                ><span class="mdi mdi-store"></span> Super Store</a
              >
            </li>
            <li class="nav-item">
              <nuxt-link to="/" class="nav-link">Home</nuxt-link>
            </li>
            <li class="nav-item">
              <nuxt-link to="/products" class="nav-link">Products</nuxt-link>
            </li>

            <li class="nav-item dropdown">
              <a
                class="nav-link dropdown-toggle"
                href="#"
                data-toggle="dropdown"
                aria-haspopup="true"
                aria-expanded="false"
              >
                Pages
              </a>
              <div class="dropdown-menu">
                <a class="dropdown-item" href="shop.html"
                  ><i class="mdi mdi-chevron-right" aria-hidden="true"></i> Shop
                  Grid</a
                >
                <a class="dropdown-item" href="single.html"
                  ><i class="mdi mdi-chevron-right" aria-hidden="true"></i>
                  Single Product</a
                >
                <a class="dropdown-item" href="cart.html"
                  ><i class="mdi mdi-chevron-right" aria-hidden="true"></i>
                  Shopping Cart</a
                >
                <a class="dropdown-item" href="checkout.html"
                  ><i class="mdi mdi-chevron-right" aria-hidden="true"></i>
                  Checkout</a
                >
              </div>
            </li>
          </ul>
        </div>
      </div>
    </nav>
</template>