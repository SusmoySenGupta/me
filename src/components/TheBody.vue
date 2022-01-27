<script setup>
const name = `<susmoy/>`;
const designation = `Software Engineer`;
</script>
<template>
    <section class="fixed inset-0 flex flex-col items-center justify-center">
        <h1 class="font-mono text-4xl md:text-6xl text-slate-100">{{ name }}</h1>
        <h3 class="mt-4 font-mono text-sm md:text-xl text-slate-100">{{ designation }}</h3>
    </section>
</template>