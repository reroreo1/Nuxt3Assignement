<template>
<div class="flex items-center gap-[32px] container mx-auto">
    <div class="bg-[#54A6FF] flex-1 cartone-1 h-[360px] rounded-xl mx-10 my-5">
        <span class="text-7xl max-width:[600px]">The Best Platform for Car Rental</span>
    </div>
    <!-- <div class="bg-[#3563E9] hidden md:block md:flex-1 cartone-2 h-[360px]  mx-7 my-5 rounded-xl"> -->
    <!-- </div> -->
</div>

</template>
<style>
.cartone-1 {

    background-image: url("../assets/patterns.png");
    animation: animateScale 15s infinite ease-in-out;
}

/* .cartone-2 {
    background-image: url("../assets/BG.png");
    background-size: 105% 105%;
    background-position: 30% 30%;
    animation: Move 7s ease-in-out infinite;
} */

@keyframes animateScale {
    0% {
        background-size: 100%;
    }

    25% {
        background-size: 110%;

    }

    50% {
        background-size: 120%;

    }

    75% {
        background-size: 110%;
    }

    100% {
        background-size: 100%;

    }
}

@keyframes Move { 
    0% {
        background-position: 0% 0%;
    }

    25% {
        background-position: 100% 0%;
    }

    50% {
        background-position: 120% 0%;

    }

    75% {
        background-position: 100% 0%;
    }

    100% {
        background-position: 0% 0%;
    }
}
</style>