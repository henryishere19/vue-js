<template>
        <h1 class="text-4xl font-bold"> Welcome {{ name }}</h1>   
        <Nav></Nav>
</template>

<script>
import Nav from '../Shared/Nav.vue'
export default {
    components: {Nav},
    props: {
        name: String
    }
}
</script>