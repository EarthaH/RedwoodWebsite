<template>
    <nav class="navbar container is-fixed-top" role="navigation" aria-label="main navigation">
        <div id="navbar" class="navbar-menu">
            <div class="navbar-start">
                <router-link to="/" class="navbar-item">Home</router-link>
            </div>
            <div class="navbar-end">
                <router-link to="/about" class="navbar-item">About</router-link>
                <router-link to="/about" class="navbar-item">Gallery</router-link>
                <router-link to="/about" class="navbar-item">Pricing</router-link>
                <router-link to="/about" class="navbar-item">Location</router-link>
                <router-link to="/about" class="navbar-item">Contact</router-link>
            </div>
        </div>
    </nav>
</template>
<script>
export default {
    name: 'NavComponent',
    methods: {
    }
};
</script>

<style lang="scss" scoped src="../styles/styles.scss"></style>
