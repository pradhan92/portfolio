<template>
    <div>
         <div><Navbar/></div>
           <div> <slot></slot></div>
           <div> <Footer/></div>
    </div>
</template>

<script setup>
import { onMounted } from "vue";
import { initFlowbite } from "flowbite";

onMounted(() => {
    initFlowbite();
});
</script>

<style>

</style>