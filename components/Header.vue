<template>
    <div>
        <ul class="nav-items">
            <li>
                <nuxt-link to="/">Home</nuxt-link>
            </li>
            <li>
                <nuxt-link to="/products">Products</nuxt-link>
            </li>
        </ul>
    </div>
</template>

<style scoped>

    .nav-items {
        list-style: none;
        padding: 0;
        margin: 0;
        height: 60px;
        display: flex;
        justify-content: space-around;
        align-items: center;
        background-color:blanchedalmond;
        text-decoration: none;
        color: black;
    }

    .nav-items: hover {
        color: red;
    }

</style>
