<template>
  <main class="bg-black bg-opacity-50 w-full min-h-screen">
    <header class="py-20 gap-12 flex flex-col md:flex-row items-center container mx-auto px-6">
      <div class="w-full md:w-1/2">
        <img src="/main.png" class="md:w-4/5 lg:3/5" alt="Sonke Image">
      </div>

      <div class="w-full md:w-1/2">
        <img src="/title.svg" class="w-full" alt="">

        <div class="flex items-center gap-5 mt-12">
          <nuxt-link to="https://t.me/Sonkeonsolana" class="text-xl bg-[#5296b4] rounded-md border border- px-5 py-3 text-white hover:bg-[#b36ad5] flex gap-3 duration-500 ease-in-out">
            <IconsTelegram class="w-7 h-7"/>
            Telegram
          </nuxt-link>
          <nuxt-link to="https://x.com/sonkeonsol" class="text-xl bg-[#5296b4] rounded-md border border- px-5 py-3 text-white hover:bg-[#b36ad5] flex gap-3 duration-500 ease-in-out">
            <IconsTwitter class="w-7 h-7"/>
            Twitter
          </nuxt-link>
        </div>
      </div>
    </header>
    <section class="grid md:grid-cols-2 gap-12 px-6 py-20 container mx-auto">
      <div class="bg-white bg-opacity-[10%] p-6 rounded-xl w-full">
        <img src="/about.svg" class="h-16 mx-auto -mt-14" alt="">
        <p class="text-xl text-white mt-5">
          Get ready,Bonk and Honk equal SONKE a monkey that create unity and spread love among people.<br />
          Join us on this incredible journey backed by innovation and a rebust community
        </p>
      </div>

      <div class="bg-white bg-opacity-[10%] p-6 rounded-xl w-full">
        <img src="/roadmap.svg" class="h-16 mx-auto -mt-14" alt="">
        <p class="text-xl text-white mt-5">
          TOTAL SUPPLY 1,000,000,000<br />
          NAME: SONKE<br />
          SYMBOL $SONKE<br />
          DECIMAL 9<br />
          NETWORK: SOLANA CHAIN<br />
          TAX 0/0<br />
        </p>
      </div>
    </section>
    <footer class="p-6 container py-20 mx-auto ">
      <p class="text-xl text-white bg-white bg-opacity-[10%] rounded-xl p-5">
        Disclaimer: This token is simply paying homage to a meme with intention of spreading love among people. Do your own research and be fully responsible for everyloss you encounter
      </p>
    </footer>
  </main>
</template>
<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap');

body {
  background: url('/bg.svg');
  background-size: cover;
  background-position: center;
}

* {
  font-family: 'Poppins', sans-serif;
}
/* 
.button {
  border-radius: 38px;
  background: #61b1d4;
  box-shadow:  -10px 10px 20px #5296b4,
             10px -10px 20px #70ccf4; */
/* } */
/* 61b1d4 blue */
/* b36ad5 purple */
</style>
