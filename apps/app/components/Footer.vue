<template>
    <div class="flex justify-center">
        <div class="font-SpaceGrotesk flex flex-col items-center w-full md:max-w-[1536px] pt-12">
            <img class="md:hidden z-10" src="@/assets/logo1.svg" />
            <ul
                class="bg-[#000] min-h-[120px] md:min-h-12 z-10 flex flex-col md:flex-row py-5 md:pb-0 justify-between items-center md:items-start px-10 min-w-[40%] text-white">
                <li><nuxt-link to="/" class="nav-link">Dashboard</nuxt-link></li>
                <li><nuxt-link to="/verify" class="nav-link">Verify Proof</nuxt-link></li>
                <li><nuxt-link to="https://0xzero.org" class="nav-link">Home Page</nuxt-link></li>
            </ul>
            <div
                class="bg-[#000] min-h-[120px] z-10 flex flex-col md:pb-0 md:flex-row justify-between items-center px-10 w-full text-white">

                <div class="flex w-[136px]">
                    <img class="hidden md:block" src="@/assets/logo1.svg" />
                </div>
                <div class="my-2">
                    <h1 class="text-center">Copyright © 2024 · All Rights Reserved</h1>
                </div>
                <div class="flex flex-row justify-evenly md:justify-end gap-5 items-center text-white w-[136px]">
                    <a href="http://" target="_blank" rel="noopener noreferrer">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="white" viewBox="0 0 640 512"
                            class="w-6 h-6 text-white">
                            <path
                                d="M524.5 69.8a1.5 1.5 0 0 0 -.8-.7A485.1 485.1 0 0 0 404.1 32a1.8 1.8 0 0 0 -1.9 .9 337.5 337.5 0 0 0 -14.9 30.6 447.8 447.8 0 0 0 -134.4 0 309.5 309.5 0 0 0 -15.1-30.6 1.9 1.9 0 0 0 -1.9-.9A483.7 483.7 0 0 0 116.1 69.1a1.7 1.7 0 0 0 -.8 .7C39.1 183.7 18.2 294.7 28.4 404.4a2 2 0 0 0 .8 1.4A487.7 487.7 0 0 0 176 479.9a1.9 1.9 0 0 0 2.1-.7A348.2 348.2 0 0 0 208.1 430.4a1.9 1.9 0 0 0 -1-2.6 321.2 321.2 0 0 1 -45.9-21.9 1.9 1.9 0 0 1 -.2-3.1c3.1-2.3 6.2-4.7 9.1-7.1a1.8 1.8 0 0 1 1.9-.3c96.2 43.9 200.4 43.9 295.5 0a1.8 1.8 0 0 1 1.9 .2c2.9 2.4 6 4.9 9.1 7.2a1.9 1.9 0 0 1 -.2 3.1 301.4 301.4 0 0 1 -45.9 21.8 1.9 1.9 0 0 0 -1 2.6 391.1 391.1 0 0 0 30 48.8 1.9 1.9 0 0 0 2.1 .7A486 486 0 0 0 610.7 405.7a1.9 1.9 0 0 0 .8-1.4C623.7 277.6 590.9 167.5 524.5 69.8zM222.5 337.6c-29 0-52.8-26.6-52.8-59.2S193.1 219.1 222.5 219.1c29.7 0 53.3 26.8 52.8 59.2C275.3 311 251.9 337.6 222.5 337.6zm195.4 0c-29 0-52.8-26.6-52.8-59.2S388.4 219.1 417.9 219.1c29.7 0 53.3 26.8 52.8 59.2C470.7 311 447.5 337.6 417.9 337.6z" />
                        </svg></a>
                    <a href="http://x.com/0xzeroorg" target="_blank" rel="noopener noreferrer">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" class="w-6 h-6 text-white"
                            fill="currentColor">
                            <path
                                d="M389.2 48h70.6L305.6 224.2 487 464H345L233.7 318.6 106.5 464H35.8L200.7 275.5 26.8 48H172.4L272.9 180.9 389.2 48zM364.4 421.8h39.1L151.1 88h-42L364.4 421.8z" />
                        </svg>
                    </a>
                </div>
            </div>
        </div>
    </div>
</template>
