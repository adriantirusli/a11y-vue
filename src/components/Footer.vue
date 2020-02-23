<template>
    <v-footer
        absolute
        class="font-weight-medium"
        dark
        role="contentInfo"
    >
        <v-col
        class="text-center"
        cols="12"
        >
        {{ new Date().getFullYear() }} — <strong>Footer</strong>
        </v-col>
    </v-footer>
</template>

<script>
export default {
    name: 'Footer'
}
</script>