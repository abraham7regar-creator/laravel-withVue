<template>
    <div>
        <nav class="navbar bg-white border-bottom navbar-light">
            <router-link class="navbar-brand mr-auto" :to="{name:'home'}">Blog</router-link>
            <router-link class="btn nav-button" :to="{name:'second'}">About</router-link>
        </nav>
        <div class="container mb-4 mt-4 ml-4 mr-4">
            <router-view></router-view>
        </div>
    </div>
</template>