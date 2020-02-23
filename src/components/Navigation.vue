<template>
    <div>
        <v-btn
            v-for="nav in navs"
            :key="nav.title"
            href="#"
            target="_blank"
            text
        >
            <span class="mr-2">{{nav.title}}</span>
        </v-btn>
    </div>
</template>

<script>
export default {
    name: 'Navigation',
    data(){
        return{
            navs: [
                { title: 'Dashboard'},
                { title: 'Page'},
                { title: 'Form'},
            ]
        }
    }
}
</script>