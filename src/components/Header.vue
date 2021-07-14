<template>
    <div class="header col-start-1 col-end-5 pt-2.5 flex justify-between items-center text-gray-600">
        <!-- Page title -->
        <div class="flex text-2xl font-extrabold w-sm text-black">
            [OCR]
        </div>
        <!-- Pages -->
        <div class="hidden md:flex space-x-8 text-sm font-medium ml-8">
            <a href="#" class="hover:underline">
                <strong>Dashboard</strong>
            </a>
            <a href="#" class="hover:underline">
                About
            </a>
            <a href="#" class="hover:underline">
                Contact
            </a>
        </div>
        <!-- Languages -->
        <div class="hidden md:flex space-x-2 text-sm w-sm font-medium">
            <a href="#" class="hover:underline">
                <strong>EN </strong>
            </a>&nbsp;\
             <a href="#" class="hover:underline">
                DE 
            </a>&nbsp;\
            <a href="#" class="hover:underline">
                FR 
            </a>&nbsp;\
            <a href="#" class="hover:underline">
                IT
            </a>
        </div>
        <!-- Hamburger button (mobile) -->
        <div class="md:hidden flex items-center">
            <button class="mobile-menu-button" @click="toggleButton()">
                <i class="fas fa-bars"></i>
            </button>
        </div>

        <!-- Mobile menu -->
        <div class="mobile-menu hidden flex">
            <a href="#" class="block py-2 px-4 text-sm hover:bg-gray-200">Dashboard</a>
            <a href="#" class="block py-2 px-4 text-sm hover:bg-gray-200">About</a>
            <a href="#" class="block py-2 px-4 text-sm hover:bg-gray-200">Contact</a>
        </div>

    </div>
</template>

<script>
export default {
    name: 'Header',
    methods: {
        toggleButton() {
            const menu = document.querySelector('.mobile-menu');
            menu.classList.toggle("hidden");
        }
    }
}
</script>
