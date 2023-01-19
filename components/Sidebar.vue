<template>
    <div class="flex gap-1 sticky">

        <!-- <div class="relative w-64 bg-black h-screen text-white main-sidebar">
            <div class="flex logo-section mb-16">
                <img src="@/assets/Earth-logo.png" class="" alt="site logo" />
                <span class="self-center site-name">Craft it</span>
            </div>
            <div class="nav-items-section">
                <div class="flex mb-16 px-3.5 py-3 font-normal active">
                    <img src="@/assets/dashboard.png" class="bg-white" alt="dashboard">
                    <a href="" class="nav-link ml-9">Dashboard</a>
                </div>
                <div class="flex mb-16 px-3.5 py-3 font-normal">
                    <img src="@/assets/dashboard.png" class="bg-white" alt="dashboard">
                    <a href="" class="nav-link ml-9">Template</a>
                </div>
                <div class="flex mb-16 px-3.5 py-3 ">
                    <img src="@/assets/dashboard.png" class="bg-white" alt="dashboard">
                    <a href="" class="nav-link ml-9">Document</a>
                </div>
                <div class="flex mb-16 px-3.5 py-3">
                    <img src="@/assets/dashboard.png" class="bg-white" alt="dashboard">
                    <a href="" class="nav-link ml-9">Billing</a>
                </div>
                <div class="flex mb-16 px-3.5 py-3">
                    <img src="@/assets/dashboard.png" class="bg-white" alt="dashboard">
                    <a href="" class="nav-link ml-9">Profile</a>
                </div>
            </div>
            <div class="absolute bottom-10">
                <div class="flex px-3.5">
                    <img src="@/assets/dashboard.png" class="bg-white" alt="dashboard">
                    <a href="" class="logout self-center">Logout</a>
                </div>
            </div>
        </div> -->

        <div class="fixed w-28 -w-1.5 bg-black h-screen text-white small-sidebar">
            <div class="flex justify-center logo-section mb-16">
                <img src="@/assets/Earth-logo.png" class="" alt="site logo" />
            </div>

            <div class="nav-items-section">
                <div class="flex justify-center active px-3.5 py-3 mb-16 rounded-[10px]">
                    <img src="@/assets/dashboard.png" class="bg-white" alt="dashboard">
                </div>
                <div class="flex justify-center px-3.5 py-3 mb-16">
                    <img src="@/assets/dashboard.png" class=" bg-white" alt="dashboard">

                </div>
                <div class="flex justify-center px-3.5 py-3 mb-16">
                    <img src="@/assets/dashboard.png" class=" bg-white" alt="dashboard">

                </div>
                <div class="flex justify-center px-3.5 py-3 mb-16">
                    <img src="@/assets/dashboard.png" class=" bg-white" alt="dashboard">

                </div>
                <div class="flex justify-center px-3.5 py-3 mb-16">
                    <img src="@/assets/dashboard.png" class=" bg-white" alt="dashboard">
                </div>
            </div>

            <div class="flex absolute bottom-10 left-9">
                <img src="@/assets/dashboard.png" class="bg-blue-300" alt="dashboard">
            </div>

        </div>
    </div>

</template>

<style scoped>
.main-sidebar {
    padding: 2.3rem 1.5rem;
}

.small-sidebar {
    padding: 2.3rem 1.5rem;
}

.site-name {
    font-family: sans-serif;
    font-size: 31px;
    font-weight: 600;
    line-height: 47px;
    margin-left: 1.5rem;
    letter-spacing: 0em;
    text-align: left;

}

.main-sidebar .nav-link {
    font-size: 20px;
    font-weight: 400;
    line-height: 30px;
    letter-spacing: 0em;

}

.logout {
    font-size: 15px;
    font-weight: 400;
    line-height: 22px;
    margin-left: 18px;
}

.active {
    background-color: #fff;
    border-radius: 10px;
    color: #000;
}

.active .nav-link {
    font-weight: 600 !important;
}
</style>