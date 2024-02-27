
<template>
    <TopNav/>
<!--    <AddScrollable/>-->
    <div
        :class="route.fullPath === '/' ? '' : ''"
        class="   w-[150%] px-0 flex "
    >
        <div>
        </div>
        <slot />
    </div>
</template>

<script setup>
const route = useRoute()
</script>
