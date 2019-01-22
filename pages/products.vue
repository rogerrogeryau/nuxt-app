<template>
    <div>
        <!-- <nuxt-child>      -->
            <!-- <h1>
                This is Product landing page
            </h1>
            <h1>
                <input type="text" v-model="productID">
                <button @click="submit">GO</button>
            </h1>

            <p></p> -->
            <!-- <ul>
                <li>
                    <button @click="$router.push('/products/1')">Product ID: 1</button>
                </li>
                <li>
                    <button @click="$router.push('/products/2')">Product ID: 2</button>
                </li>
            </ul> -->
            <!-- <nuxt-child/> -->
            <!-- <nuxt-child/> -->



        <section class="container">
            <!-- <nuxt-link to="/products">Products</nuxt-link> -->
            <!-- <button @click="$router.push('/products')">Go To Product</button>
            -->
            <h1>this is Product.vue</h1>
            <p></p>
                <input type="text" v-model="productID">
                <button @click="submit">GO to specific ID</button>
            
            
        </section>
        
        <section class="container">
            <nuxt-child/>
        </section>
    </div>
</template>

<script>
export default {
    data(){
        return {
            productID:'',
        }
    },
    methods:{
        submit(){
            this.$router.push(`/products/${this.productID}`);
        }
    }
}
</script>
