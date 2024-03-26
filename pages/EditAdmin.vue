<template>
  <div class="flex justify-center items-center h-[100vh] bg-[#E9EAEC]" style="">
    <div class="px-[30px] max-w-[460px] w-[100%] relative py-[30px] rounded-[30px] h-auto bg-white">
      <img src="/close.png" class="absolute right-[10px] top-[10px]" alt="">

      <div class="mx-auto w-[70%]">
        <h1 class="font-semibold text-[35px] leading-[45px]">Редактирование
          сотрудника</h1>
        <p class="leading-[2] text-[#91939D]">Логин</p>
        <input type="text" placeholder="Логин" class=" w-[100%] bg-[#E9EAEC] px-[15px] py-[6px] rounded-[10px]">
        <p class="leading-[2] text-[#91939D]">Email</p>
        <input type="text" placeholder="Email" class=" w-[100%] bg-[#E9EAEC] px-[15px] py-[6px] rounded-[10px]">

        <p class="leading-[2] text-[#91939D]">Группа</p>
        <input type="text" placeholder="Группа сотрудника" class=" w-[100%] bg-[#E9EAEC] px-[15px] py-[6px] rounded-[10px]">

        <button class="mt-[20px] w-[100%] py-[5px] rounded-[10px] text-white bg-[#FF185F] mx-auto ">Редактировать</button>
        <button class="mt-[20px] w-[100%] py-[5px] rounded-[10px] text-black bg-[#E9EAEC] mx-auto ">Удалить</button>
      </div>
    </div>
  </div>

</template>
<style>
.container {
  display: block;
  position: relative;
  padding-left: 35px;
  margin-bottom: 12px;
  cursor: pointer;
  font-size: 14px;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

/* Hide the browser's default checkbox */
.container input {
  position: absolute;
  opacity: 0;
  cursor: pointer;
  height: 0;
  width: 0;
}

/* Create a custom checkbox */
.checkmark {
  position: absolute;
  top: 0;
  left: 0;
  height: 20px;
  width: 20px;
  border-radius: 6px;
  background: #E9EAEC;
  transition: 0.3s;
}

/* On mouse-over, add a grey background color */
.container:hover input ~ .checkmark {
  background-color: #1a1a1a;
}

/* When the checkbox is checked, add a blue background */
.container input:checked ~ .checkmark {
  background-color: #000000;
}

/* Create the checkmark/indicator (hidden when not checked) */
.checkmark:after {
  content: "";
  position: absolute;
  display: none;
}

/* Show the checkmark when checked */
.container input:checked ~ .checkmark:after {
  display: block;
}

/* Style the checkmark/indicator */
.container .checkmark:after {
  left: 8px;
  top: 4px;
  width: 5px;
  height: 10px;
  border: solid white;
  border-width: 0 2px 2px 0;
  -webkit-transform: rotate(45deg);
  -ms-transform: rotate(45deg);
  transform: rotate(45deg);
}
</style>
<script setup lang="ts">
</script>
