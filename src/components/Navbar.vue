<template>
    <nav>
        <ul>
            <li> <router-link to="/">Home</router-link> </li>
            <li> <router-link to="/tasks/new">New</router-link> </li>
        </ul>
    </nav>
</template>

<script lang="ts">
    import { defineComponent } from "@vue/runtime-core";

    export default defineComponent({
        name: "NavbarMain"
    })
</script>