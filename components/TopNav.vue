<template>
  <div class="py-2 px-4 flex flex-row align-center justify-between">
    <div><img src="../static/logo.png" width="150" alt="" srcset=""></div>
    <div>
        <ul class="flex flex-row text-sm">
            <nuxt-link to="/" class="py-2 px-2 m-2 text-[color:var(--primary)]">Become a host</nuxt-link>
            <nuxt-link to="/" class="py-2 px-2 m-2">Account</nuxt-link>
            <nuxt-link to="/" class="py-2 px-2 m-2">Kwacha</nuxt-link>
            <nuxt-link to="/" class="py-2 px-2 m-2">Eng</nuxt-link>
            <nuxt-link to="/auth/login" class="py-2 px-2 m-2">Logout</nuxt-link>
        </ul>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>