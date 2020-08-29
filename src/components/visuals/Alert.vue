<template>
    <div class="alert" :class="'alert-' + type">
        <slot />
    </div>
</template>

<script>
    export default {
        name: "Alert",
        props: ["type"]
    }
</script>

<style scoped>
    .alert {
        @apply border m-8 p-4 shadow-xl;
    }
    .alert-warning {
        @apply bg-yellow-100 border-yellow-300;
    }
</style>