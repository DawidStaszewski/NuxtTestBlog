<template>
    <div class="Main">
        <Header />
        <div class="Content">
            <slot />
        </div>

        <Header />
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.Content {
    min-height: 400px;
    background: #c97777;
}
</style>
