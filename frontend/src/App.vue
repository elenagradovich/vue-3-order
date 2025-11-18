<template>
    <div>
        <app-layout>
            <home-view />
        </app-layout>
    </div>
</template>

<style lang="scss">
    @use "@/assets/scss/app.scss" as *;
</style>

<script setup>
    import { AppLayout } from "@/layouts";
    import { HomeView } from "@/views";
</script>
