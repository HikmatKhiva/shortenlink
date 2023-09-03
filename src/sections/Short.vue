<template>
    <section id="short" class="bg-[#eff0f5] pb-10">
        <div class="container mx-auto">
            <!-- Form -->
            <form
                class="bg-shorten-desktop bg-center bg-no-repeat bg-cover -translate-y-14 bg-dark-violet  flex items-center gap-5 p-10 rounded ">
                <input placeholder="Shorten a link here" type="text"
                    class="text-lg py-2 px-5  flex-grow rounded outline-none">
                <Button class="py-2 px-5 rounded text-lg">Shorten it!</Button>
            </form>
            <div class="flex flex-col gap-5">
                <Link />
            </div>
            <div class="text-center pt-10 font-poppins">
                <h2 class="text-4xl font-medium">Advanced Statistics</h2>
                <p class="text-sm text-gray-violet mt-3">Track how your links are performing across the web with <br>
                    our advanced statistics dashboard.</p>
            </div>
        </div>
    </section>
</template>

<script setup>
import Link from '../components/Link.vue';
import Button from '../ui-components/Button.vue';
</script>

