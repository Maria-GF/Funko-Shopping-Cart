<script setup>
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'
</script>

<template>
  <Header />
<main class="products products__container">
    <h2 class="products__heading">Nuestra colección</h2>
    <div class="products__grid">
        <div class="product">
            <img class="product__image" src="/img/fbarbie.png" alt="image product">
            <div class="product_content">
                <h3 class="product__name">Barbie</h3>
                <p class="product__description">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Excepturi iusto ipsum doloribus molestias optio nisi blanditiis voluptates.</p>
                <p class="product__price">150€</p>
                <a class="product__link" href="#">Añadir carrito</a>
            </div>
        </div> <!--product-->
        <div class="product">
            <img class="product__image" src="/img/fmusical.jpg" alt="image product">
            <div class="product_content">
                <h3 class="product__name">Barbie</h3>
                <p class="product__description">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Excepturi iusto ipsum doloribus molestias optio nisi blanditiis voluptates.</p>
                <p class="product__price">150€</p>
                <a class="product__link" href="#">Añadir carrito</a>
            </div>
        </div> <!--product-->
        <div class="product">
            <img class="product__image" src="/img/fmiercoles.png" alt="image product">
            <div class="product_content">
                <h3 class="product__name">Barbie</h3>
                <p class="product__description">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Excepturi iusto ipsum doloribus molestias optio nisi blanditiis voluptates.</p>
                <p class="product__price">150€</p>
                <a class="product__link" href="#">Añadir carrito</a>
            </div>
        </div> <!--product-->
    </div> <!--product grid-->
</main>
<Footer />
</template>

