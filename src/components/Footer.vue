<template>
    <v-card height="150">
        <v-footer
            absolute
            class="font-weight-medium"
            dark
        >
            <v-col
            class="text-center"
            cols="12"
            >
            {{ new Date().getFullYear() }} — <strong>Footer</strong>
            </v-col>
        </v-footer>
    </v-card>
</template>

<script>
export default {
    name: 'Footer'
}
</script>