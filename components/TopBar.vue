<template>
    <div class="flex items-center justify-between p-4 bg-green-100">
    <div class="flex items-center">
        <span class="text-lg font-semibold">Sales Admin</span>
        <i class="fas fa-chevron-down ml-2"></i>
    </div>
    <div class="flex items-center space-x-4">
        <div class="relative">
            <input type="text" placeholder="Search anything in Sohoma..." class="border rounded-full py-2 px-4 pl-10 w-80">
            <i class="fas fa-search absolute left-3 top-1/2 transform -translate-y-1/2 text-gray-400"></i>
        </div>
        <i class="fas fa-sync-alt text-xl"></i>
        <i class="fas fa-question-circle text-xl"></i>
        <button class="flex items-center bg-black text-white py-2 px-4 rounded-full">
            <i class="fas fa-plus mr-2"></i>
            Add new product
        </button>
    </div>
</div>
</template>