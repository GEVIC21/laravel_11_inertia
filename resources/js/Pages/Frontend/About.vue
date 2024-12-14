<template>
    <Frontend>
        <Head>
            <title>About Page</title>
        </Head>
        <h1>{{title}}</h1>
    </Frontend>
</template>

<script setup>
import Frontend from '@/Layouts/FrontendLayout.vue';
import {Head} from '@inertiajs/vue3';

defineProps({
    title: String
})

</script>

