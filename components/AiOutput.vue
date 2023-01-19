<template>
    <div class="overflow-y-auto">
        <div class="ml-11 mr-14">
            <div class="bg-[#FFFBF5] py-6 px-8">
                <div class="grid grid-cols-2 gap-9">
                    <div class="w-full flex justify-between overflow-hidden border mx-auto">
                        <button class="bg-white px-5">
                            <img src="@/assets/Search.png" alt="" class="opacity-50">
                        </button>
                        <input type="text" class="py-3 px-4 w-full text-[1.25rem] focus:outline-none"
                            placeholder="Search ">
                    </div>
                    <div>
                        <select id="countries"
                            class="bg-white border py-3 px-4 text-[1.25rem] focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500">
                            <option selected>Category</option>
                            <option value="US">United States</option>
                            <option value="CA">Canada</option>
                            <option value="FR">France</option>
                            <option value="DE">Germany</option>
                        </select>
                    </div>
                    <!-- <div> <input type="text" class="w-full border-1 " placeholder="Search"></div>
                    <div> jhjkahgak</div> -->
                </div>
            </div>

            <div class="grid grid-cols-3 gap-4">
                <div class="bg-gray-200">
                    <div class="flex justify-between">
                        <div class="flex ">
                            <span class="bg-[#263238] p-3 inline-block rounded-[5px]">
                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" class="w-7">
                                    <path fill="#fff"
                                        d="M20.71,7.04C21.1,6.65 21.1,6 20.71,5.63L18.37,3.29C18,2.9 17.35,2.9 16.96,3.29L15.12,5.12L18.87,8.87M3,17.25V21H6.75L17.81,9.93L14.06,6.18L3,17.25Z" />
                                </svg>
                            </span>
                            <span class="text-[1.25rem] font-medium ml-2.5 self-center">
                                Blog Intro
                            </span>
                        </div>
                        <div class="">

                        </div>

                    </div>
                </div>
            </div>

        </div>
    </div>
</template>

<style scoped>
.border {
    border: 1.5px solid rgba(0, 0, 0, .5);
}
</style>