<template>
    <v-toolbar>
        <!-- <template v-slot:prepend>
            <div class="text-h5">Title</div>
        </template> -->
        <v-toolbar-title>My Home</v-toolbar-title>

        <v-spacer></v-spacer>

        <v-spacer></v-spacer>

        <v-toolbar-items>
            <v-btn variant="text">News</v-btn>
            <v-btn variant="text">Blog</v-btn>
            <v-btn variant="text">Music</v-btn>
        </v-toolbar-items>
        <v-app-bar-nav-icon class="ms-2"></v-app-bar-nav-icon>
    </v-toolbar>

    <!-- <v-parallax src="https://cdn.vuetifyjs.com/images/parallax/material.jpg"></v-parallax> -->
</template>

<script setup>
</script>

<style scoped>
.v-toolbar {
    background-color: #fff;
    padding-left: 15%;
    padding-right: 15%;
}
</style>
