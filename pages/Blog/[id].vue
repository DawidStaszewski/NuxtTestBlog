<script setup lang="ts">
import { useRoute } from "vue-router";
const route = useRoute();
console.log(route.params.id);
</script>

<template>
    <div>
        BLOGIDPAGE {{ route.params.id }}
    </div>
</template>



<style></style>