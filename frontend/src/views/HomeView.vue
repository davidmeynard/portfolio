<template>
    <main>
        <p>Hi ! I'm</p>
        <h1>Meynard David</h1>
        <h2>Full Stack Web Developer</h2>

        <button>LinkedIn</button>
        <button>Github</button>
        <button>Email</button>

        <br>

        <RouterLink to="/aboutme">About me</RouterLink>
        <RouterLink to="/projects">Projects</RouterLink>



    </main>
</template>

<script>

import { RouterLink } from 'vue-router';
export default {
    components:{
        RouterLink
    }
}
</script>