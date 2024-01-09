<template>
    <v-navigation-drawer>
        <v-list>
            <v-list-item title="Home" v-bind:to="{ name: 'home' }" />
            <v-list-item title="Menu" v-bind:to="{ name: 'menu' }" />
            <v-list-item title="About" v-bind:to="{ name: 'about' }" />
            <v-list-item title="Admin" v-bind:to="{ name: 'admin' }" />
        </v-list>
    </v-navigation-drawer>
</template>