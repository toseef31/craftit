<template>
    <div class="flex">
        <div class="w-28 -w-1.5">
            <Sidebar />
        </div>
        <div class="w-full">
            <NavBar />
            <slot />
        </div>
    </div>
</template>