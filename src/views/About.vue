<script setup>
import { useRouter } from 'vue-router';
const router=useRouter();
const goToContact=()=>{
    router.push('/contact')
}
</script>

<template>

<div>About page</div>
<button @click="goToContact">Got to contact</button>

</template>

<style>

</style>