<template>
    <NavBar></NavBar>
    <div class="content">
        <nav>
            <img src="./assets/background.svg" alt="">
            <div class="container_ball">
                <div class="ball"></div>
            </div>
        </nav>
    </div>
</template>

<script>
import NavBar from "./components/NavBar/NavBar.vue";
export default {
    name: "App",

    components: { NavBar },
};
</script>
