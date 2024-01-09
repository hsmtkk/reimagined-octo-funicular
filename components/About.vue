<template>
    <v-main>
        <v-container>
            <h3>Quality Pizza For 30 Years</h3>
            <p>Nothing but the best quality ingredients, with a friendly atmosphere.</p>
        </v-container>
        <NuxtImg src="/images/calzone.jpg" />
        <v-container>
            <h3>Click on the links below for more info</h3>
            <v-list>
                <v-list-item>
                    <NuxtLink v-bind:to="{ name: 'about-history' }">Our history</NuxtLink>
                </v-list-item>
                <v-list-item>
                    <NuxtLink v-bind:to="{ name: 'about-delivery' }">Delivery</NuxtLink>
                </v-list-item>
                <v-list-item>
                    <NuxtLink v-bind:to="{ name: 'about-locations' }">Locations</NuxtLink>
                </v-list-item>
            </v-list>
        </v-container>
    </v-main>
</template>