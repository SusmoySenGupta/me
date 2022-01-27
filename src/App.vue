
<script setup>
import SocialLinks from './components/SocialLinks.vue';
import TheHeader from './components/TheHeader.vue';
import TheBody from './components/TheBody.vue';
import { useTitle } from '@vueuse/core';

useTitle('Susmoy Sen Gupta | Software Engineer');
</script>

<template>
    <div class="flex flex-col items-center justify-center w-screen h-screen bg-slate-800" v-once>
        <the-header></the-header>
        <the-body></the-body>
        <social-links></social-links>
    </div>
</template>