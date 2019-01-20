<template>
    <v-container grid-list-md text-xs-center fill-height="true">
        <v-layout row wrap>
            <v-flex v-for="i in 2" :key="`6${i}`" xs6>
                <v-card dark color="primary" height="100%">
                    <v-card-text class="px-0"></v-card-text>
                </v-card>
            </v-flex>
        </v-layout>
    </v-container>
</template>
