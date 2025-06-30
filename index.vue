<template>
    <v-container>
        <v-row>
            <v-col>
                <v-card to="/appbar/" >
                    <v-card-text>
                        <h1>appbar</h1>
                    </v-card-text>
                </v-card>
            </v-col>
            <v-col>
                <v-card to="/card/">
                    <v-card-text>
                        <h1>card</h1>
                    </v-card-text>
                </v-card>
            </v-col>
            <v-col>
                <v-card to="/slide-group/">
                    <v-card-text>
                        <h1>slide group</h1>
                    </v-card-text>
                </v-card>
            </v-col>
            <v-col>
                <v-card to="/service/">
                    <v-card-text>
                        <h1>service</h1>
                    </v-card-text>
                </v-card>
            </v-col>
            <v-col>
                <v-card to="/about/">
                    <v-card-text>
                        <h1>about</h1>
                    </v-card-text>
                </v-card>
            </v-col>
            <v-col>
                <v-card to="/footer/">
                    <v-card-text>
                        <h1>footer</h1>
                    </v-card-text>
                </v-card>
            </v-col>
            <v-col>
                <v-card to="/contact/">
                    <v-card-text>
                        <h1>contact</h1>
                    </v-card-text>
                </v-card>
            </v-col>
            <v-col>
                <v-card to="/clients/">
                    <v-card-text>
                        <h1>client</h1>
                    </v-card-text>
                </v-card>
            </v-col>
        </v-row>
    </v-container>
</template>
<script setup lang="ts">
definePageMeta({
    layout:'blank'
})

</script>

