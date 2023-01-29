<template>
    <div>
        <h1>index.vue</h1>
        <TheTest />
    </div>
</template>

<script setup lang="ts">
const { test } = useComposablesTest()
console.log(test)
</script>
