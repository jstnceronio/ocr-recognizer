<template>
    <div class="content-upload row-start-2 row-span-2 col-start-3 col-span-2 p-2.5 bg-gradient-to-r from-purple-400 via-pink-500 to-red-500">
        <div class="flex items-center justify-center bg-white-50 py-12 px-4 sm:px-6 lg:px-8 bg-no-repeat bg-cover">
	        
	        <div class="sm:max-w-lg w-full p-10 bg-white rounded-xl z-10">
            
            <div class="mt-8 space-y-3 bg-green">
                        
                <div class="grid grid-cols-1 space-y-2">
                    <label class="text-sm font-bold text-gray-500 tracking-wide text-left">Attach Document</label>
                    <div class="flex items-center justify-center w-full">
                        <label class="flex flex-col rounded-lg border-4 border-dashed w-full h-60 p-10 group text-center">
                            <div class="h-full w-full text-center flex flex-col items-center justify-center items-center">
                                <i class="far fa-file-image fa-4x text-gray-500" id="file-icon"></i>
                                <p class="pointer-none text-gray-500 "><span class="text-sm">Drag and drop</span> files here <br /> or <a href="" id="" class="text-blue-600 hover:underline">select a file</a> from your computer</p>
                            </div>
                            <input type="file" class="hidden">
                        </label>
                    </div>
                </div>
                </div>
	        </div>
        </div>
    </div>
</template>

<script>

</script>

<style scoped>

</style>