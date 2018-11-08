<template>
    <div>
        <nuxt-link to="/products/1">Load Product</nuxt-link>
        <nuxt-link to="/products/2">Load Product 2</nuxt-link>
    </div>
</template>

<script>
export default{
      data(){
        return {
        }
    },
    methods: {
        loadProduct(){
            this.$router.param('/products/1');
        }
    }
}
</script>