<template>
    <div class="flex  justify-center mt-[-1rem] ml-[120px]">
        <nav class="w-[550px] max-w-screen-lg">
            <!-- Top navigation bar -->
            <div class="flex items-center justify-between border-b border-gray-600 py-4 px-6">
                <h2 class="text-xl font-semibold text-black">Home</h2>
                <a href="#" class="text-2xl font-medium rounded-full text-white hover:bg-blue-800 hover:text-blue-300">
                    <svg class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24">
                        <!-- Twitter icon -->
                    </svg>
                </a>
            </div>

            <!-- Tweet input section -->
            <div class="flex items-start border-b border-gray-600 py-4 px-6">
                <img class="h-10 w-10 rounded-full mr-4" src="https://pbs.twimg.com/profile_images/1121328878142853120/e-rpjoJi_bigger.png" alt="" />
                <textarea class="flex-1 bg-transparent text-gray-400 font-medium text-lg" rows="2" placeholder="What's happening?"></textarea>
            </div>

            <!-- Tweet action icons -->
            <div class="flex items-center justify-between border-b border-gray-600 py-4 px-6">
                <div class="flex space-x-4">
                    <a href="#" class="group flex items-center text-blue-400 px-2 py-2 text-base leading-6 font-medium rounded-full hover:bg-blue-800 hover:text-blue-300">
                        <!-- Icon 1 -->
                    </a>
                    <a href="#" class="group flex items-center text-blue-400 px-2 py-2 text-base leading-6 font-medium rounded-full hover:bg-blue-800 hover:text-blue-300">
                        <!-- Icon 2 -->
                    </a>
                    <a href="#" class="group flex items-center text-blue-400 px-2 py-2 text-base leading-6 font-medium rounded-full hover:bg-blue-800 hover:text-blue-300">
                        <!-- Icon 3 -->
                    </a>
                    <a href="#" class="group flex items-center text-blue-400 px-2 py-2 text-base leading-6 font-medium rounded-full hover:bg-blue-800 hover:text-blue-300">
                        <!-- Icon 4 -->
                    </a>
                </div>
                <button class="bg-blue-400 hover:bg-blue-600 text-white font-bold py-2 px-8 rounded-full">
                    Tweet
                </button>
            </div>

            <!-- Placeholder for tweet feed -->
            <div class="p-6">
                <!-- Placeholder content -->
            </div>
        </nav>
    </div>
</template>


<script>
export default {
    name: 'Section'
};
</script>

<style scoped>
/* Scoped styles if needed */
</style>
