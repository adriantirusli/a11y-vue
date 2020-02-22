<template>
    <div>
        <v-content>
            <div class="d-flex align-center">
                <Main/>

                <v-spacer></v-spacer>

                <Aside/>
            </div>
        </v-content>
    </div>
</template>

<script>
import Aside from './Aside'
import Main from './Main';
export default {
    components: {
        Aside,
        Main,
    },
}
</script>