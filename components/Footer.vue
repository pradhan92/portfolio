<template>
    <div>
       <!-- TW Elements is free under AGPL, with commercial license required for specific uses. See more details: https://tw-elements.com/license/ and contact us for queries at tailwind@mdbootstrap.com --> 
    <footer
      class="bg-green-400 text-center dark:bg-green-500 lg:text-left">
      <div class="p-4 text-center text-white dark:text-neutral-200">
        © {{ currentYear }} Copyright:
        <a
          class="text-white dark:text-neutral-400"
          href="/"
          >Pradhan Tara Kumar</a
        >
      </div>
    </footer>
    </div>
</template>

<script>
export default {
    data() {
        return {
            currentYear: new Date().getFullYear()
        };
    }
};

</script>

<style >

</style>