<template>
    <x-form :id="$route.params.id" />
</template>

<script>
    import XForm from "./Form";
    export default {
        route: { path: `user/:id/edit` },
        components: { XForm },
    };
</script>

<style></style>
