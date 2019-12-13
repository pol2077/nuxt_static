<template>
    <nav class="nav">
        <div class="logo">
            <nuxt-link :to="{name: 'index'}" class="logo text-lg"> Nuxt Fundamantals</nuxt-link>

            <span class="subheader">A Vue School course</span>
        </div>
    </nav>
</template>

<script>
  export default {
    name: "TheNavbar"
  }
</script>

<style scoped>

</style>
