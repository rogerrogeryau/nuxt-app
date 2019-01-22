<template>
  <!-- <section class="container"> -->
    <div>
      <section class="container">
        <!-- <nuxt-link to="/products">Products</nuxt-link> -->
        <!-- <button @click="$router.push('/products')">Go To Product</button>
         -->
         <h1>this is Home</h1>
      </section>
    </div>
  <!-- </section> -->
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  },
  layer:'users.vue'
}
</script>

<style>

/* .container {
  min-height: 30vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
} */

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
