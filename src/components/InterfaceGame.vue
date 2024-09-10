<template>
  <div class="bg-gray-800 text-white h-screen">
    <!-- Header Section -->
    <div class="flex justify-between items-center p-4 bg-gray-900">
      <div class="flex items-center">
        <div class="rounded-full bg-yellow-400 w-12 h-12"></div>
        <div class="ml-4">
          <h1 class="text-lg">Медитотрон Рободжиства</h1>
          <p>340 / 567 душ</p>
        </div>
      </div>
      <div class="flex items-center">
        <div class="mr-4">
          <h1 class="text-lg">Фёдор Тищенко</h1>
          <p>230 / 560 HP</p>
        </div>
        <div class="rounded-full bg-green-400 w-12 h-12"></div>
      </div>
    </div>

    <!-- Battle Interface -->
    <div class="flex justify-between p-4">
      <!-- Character Image Placeholder -->
      <div class="w-1/3 bg-gray-700 h-96 flex items-center justify-center">
        <p>Character Image Zone</p>
      </div>

      <!-- Action and Log Section -->
      <div class="w-2/3 bg-gray-700 p-4 space-y-4">
        <div class="bg-gray-800 p-4 rounded-md">
          <h2>Раунд 17</h2>
          <p>1 мин 15 сек</p>
        </div>

        <div class="bg-gray-800 p-4 rounded-md">
          <h2>Сделать ход</h2>
        </div>

        <!-- Log Section -->
        <div class="bg-gray-800 p-4 rounded-md">
          <h2>История боя</h2>
          <div class="overflow-y-auto h-40">
            <p>Раунд 17 - Some battle log details...</p>
            <p>Раунд 16 - More battle log details...</p>
          </div>
        </div>
      </div>
    </div>

    <!-- Footer Section -->
    <div class="p-4 bg-gray-900 text-center">
      <button class="bg-red-600 px-4 py-2 rounded" @click="runAway">Сбежать</button>
      <button class="bg-blue-600 px-4 py-2 rounded ml-4" @click="showBattleStats">Статистика битвы</button>
    </div>
  </div>
</template>

<script setup>
const runAway = () => {
  console.log('Вы сбежали!')
}

const showBattleStats = () => {
  console.log('Показать статистику битвы')
}
</script>

<style scoped>
/* Custom styles (if needed) */
</style>