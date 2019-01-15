<template>
    <div>
        <app-header></app-header>
    </div>
</template>

<script>
    export default {
        components: {
            "app-header": () => import("@/components/app-header.vue")
        }
    }
</script>
