<template>
  <div class="flex justify-center items-center h-[100vh]" style="background: url('/Вход.png'); background-size: cover;">
    <div class="px-[30px] max-w-[460px] w-[100%] relative py-[30px] rounded-[30px] h-auto bg-white">
      <img src="/close.png" class="absolute right-[10px] top-[10px]" alt="">
      <div class="mb-[20px] p-[4px] bg-[#E9EAEC] w-[60%] mx-auto rounded-[10px]">
        <button class="bg-white py-[5px] w-1/2 rounded-[5px]">Вход</button>
        <button class="w-1/2 py-[5px]">Регистрация</button>
      </div>
      <div class="mx-auto w-[70%]">
      <p class="leading-[2] text-[#91939D]">Email</p>
      <input type="text" placeholder="Email" class=" w-[100%] bg-[#E9EAEC] px-[15px] py-[6px] rounded-[10px]">
        <button class="mt-[20px] w-[100%] py-[5px] rounded-[10px] text-white bg-[#FF185F] mx-auto ">Войти</button>
        <button  class="mt-[10px] items-center justify-center flex w-[100%] py-[5px] rounded-[10px] text-black bg-[#E9EAEC] mx-auto "><svg width="21" height="20" viewBox="0 0 21 20" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path d="M16.7108 6.02392L14.6358 15.5709C14.4791 16.2446 14.071 16.4123 13.491 16.0951L10.3292 13.822L8.80372 15.2537C8.63478 15.4186 8.49382 15.5561 8.16821 15.5561L8.3956 12.4148L14.2552 7.2491C14.5101 7.02773 14.1997 6.90459 13.8594 7.12644L6.61528 11.5768L3.49664 10.6242C2.8184 10.4177 2.80612 9.96251 3.63809 9.64483L15.8361 5.05988C16.4009 4.85336 16.895 5.18206 16.7108 6.02392Z" fill="#14151A"/>
        </svg>
          Войти через телеграм</button>
      </div>
    </div>
  </div>

</template>
<script setup lang="ts">
</script>
