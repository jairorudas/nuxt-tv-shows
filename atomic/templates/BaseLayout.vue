<template>
    <div>
        <header>
            <slot name="header"></slot>
        </header>
        <main>
            <slot name="main"></slot>
        </main>
        <footer>
            <slot name="footer"></slot>
        </footer>
    </div>
</template>

<script>
export default {
    name: 'BaseLayOut',
}
</script>

<style lang="postcss">
    html {
        background-color: #0c0c0c;
        @apply text-white
    }
</style>
