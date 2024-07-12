<template>
    <div class="Main">
        <Header />

        <nav>
            <ul>
                <li><a href="">Update Profile</a></li>
                <li><a href="">View Profile</a></li>
            </ul>
        </nav>

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
