<script setup>
import { useRouter } from 'vue-router';
const router=useRouter();
const replace=()=>{
    router.replace({ name: "home" });
}
</script>

<template>

<div>Login page</div>
<button @click="replace">replace</button>
</template>

<style>

</style>