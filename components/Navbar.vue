<template>
  <div class="w-full bg-green-700">
    <div class="container mx-auto flex justify-between">
      <div class="flex items-center py-4 w-6/12">
        <NuxtLink to="/">
          <img
            class="w-40"
            src="https://upload.wikimedia.org/wikipedia/commons/f/f0/Papa_John%27s_Logo_2019.svg"
            alt=""
          >
        </NuxtLink>
        <div class="mt-6 ml-4">
          <NuxtLink
            to="/sales"
          >
            <button
              class=" uppercase rounded-md px-4 py-1 font-mono font-extrabold text-white hover:bg-white hover:text-green-700  text-xl focus:outline-none"
            >
              Promociones
            </button>
          </NuxtLink>
          <span
            class="cursor-default text-white text-xl font-bold rounded-xl"
          >|</span>
          <NuxtLink to="/menu">
            <button
              class="uppercase rounded-md px-4 py-1 text-white font-mono text-lg font-extrabold hover:bg-white hover:text-green-700 focus:outline-none"
            >
              Menú
            </button>
          </NuxtLink>
          <span
            class="cursor-default text-white text-xl font-bold rounded-xl"
          >|</span>
          <NuxtLink
            to="/restaurants"
          >
            <button
              class="uppercase rounded-md px-4 py-1 text-white font-mono text-lg font-extrabold hover:bg-white hover:text-green-700 focus:outline-none"
            >
              Restaurantes
            </button>
          </NuxtLink>
          <span
            class="cursor-default text-white text-xl font-bold rounded-xl"
          >|</span>
          <button
            class="bg-white uppercase rounded-md px-4 py-1 font-mono font-extrabold text-green-700 text-lg focus:outline-none"
          >
            Domicilio
          </button>
        </div>
      </div>
      <div class="flex items-center justify-center w-6/12">
        <div class="flex items-center bg-green-800 h-full px-2 cursor-pointer">
          <div>
            <img
              class="w-14"
              src="https://upload.wikimedia.org/wikipedia/commons/9/99/Sample_User_Icon.png"
              alt=""
            >
          </div>
          <div>
            <div class="text-white font-bold uppercase">
              Hola,
            </div>
            <div class="text-white font-bold uppercase text-lg">
              User
            </div>
            <div class="text-gray-300 font-bold uppercase text-xs ">
              Mis ordenes
            </div>
          </div>
        </div>
        <div class="ml-14 flex items-center">
          <img class="w-14" src="https://i.pinimg.com/originals/15/bb/55/15bb559cdd28f56d7c17b00498b4a946.png" alt="">
          <div class="font-bold font-mono text-white text-2xl px-2">
            $0.00
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
