<script setup>
import { RouterLink } from 'vue-router';

defineProps({
    href: String,
    active: Boolean,
});

</script>

<template>
    <RouterLink :to="href" class="font-bold text-sm text-slate-100 hover:text-red-600 transition ease-in-out">
        <slot />
    </RouterLink>
</template>
   