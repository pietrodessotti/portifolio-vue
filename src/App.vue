<template>
    <div>
        <MountScreen />
    </div>
</template>

<script>
import MountScreen from "./components/MountScreen.vue";

export default {
    name: "App",
    components: {
        MountScreen,
    },
};
</script>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Avenir, Helvetica, Arial, sans-serif;
}
</style>
