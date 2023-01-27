<template>
    <Head>
        <title>{{ person.name }}</title>
    </Head>

    <div>
        <h1>This event is by: {{ person.name }}</h1>
    </div>
</template>
<script setup>
import { Head } from "@inertiajs/inertia-vue3";

const props = defineProps({
    person: Object
})
</script>
