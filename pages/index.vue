<template>
  <div class="grid grid-cols-4 grid-rows-4">
    <div class="col-span-3 bg-red-200">
        <div class="flex justify-between items-center mb-6">
            <div>
                <h1 class="text-2xl font-bold">Dashboard</h1>
                <p class="text-gray-500">An any way to manage sales with care and precision.</p>
            </div>
            <div class="flex items-center space-x-2">
                <i class="fas fa-calendar-alt text-gray-500"></i>
                <span class="text-gray-500">January 2024 - May 2024</span>
            </div>
        </div>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
            <div class="bg-green-900 text-white p-6 rounded-lg">
                <div class="flex items-center mb-4">
                    <i class="fas fa-circle text-red-500 mr-2"></i>
                    <span class="font-medium">Update</span>
                </div>
                <p class="text-sm mb-2">Feb 12th 2024</p>
                <p class="text-lg font-bold mb-4">Sales revenue increased <span class="text-yellow-400">40%</span> in 1 week</p>
                <a href="#" class="text-green-300">See Statistics &gt;</a>
            </div>
            <div class="bg-white p-6 rounded-lg shadow">
                <div class="flex justify-between items-center mb-4">
                    <span class="font-medium">Net Income</span>
                    <i class="fas fa-ellipsis-h text-gray-500"></i>
                </div>
                <p class="text-3xl font-bold mb-2">$193.000</p>
                <p class="text-sm text-green-500"><i class="fas fa-arrow-up"></i> +35% from last month</p>
            </div>
            <div class="bg-white p-6 rounded-lg shadow">
                <div class="flex justify-between items-center mb-4">
                    <span class="font-medium">Total Return</span>
                    <i class="fas fa-ellipsis-h text-gray-500"></i>
                </div>
                <p class="text-3xl font-bold mb-2">$32.000</p>
                <p class="text-sm text-red-500"><i class="fas fa-arrow-down"></i> -24% from last month</p>
            </div>
        </div>
    </div>
      <div class="row-span-2 bg-white rounded-lg shadow-md p-4">
        <h2 class="text-center text-lg font-semibold mb-4">Total View Performance</h2>
        <div class="relative flex justify-center items-center mb-4">
            <div class="w-40 h-40 rounded-full bg-gray-200 flex justify-center items-center">
                <div class="w-32 h-32 rounded-full bg-white flex justify-center items-center">
                    <span class="text-2xl font-bold">565K</span>
                </div>
            </div>
            <div class="absolute top-4 left-4 text-sm font-semibold">16%</div>
            <div class="absolute top-4 right-4 text-sm font-semibold">23%</div>
            <div class="absolute bottom-4 left-1/2 transform -translate-x-1/2 text-sm font-semibold">68%</div>
        </div>
        <p class="text-center text-gray-600 mb-4">Here are some tips on how to improve your score.</p>
        <button class="w-full bg-white border border-gray-300 text-gray-700 py-2 rounded-lg mb-4">Guide Views</button>
        <div class="flex justify-around text-sm text-gray-600">
            <div class="flex items-center">
                <div class="w-3 h-3 bg-green-500 rounded-full mr-2"></div>
                <span>View Count</span>
            </div>
            <div class="flex items-center">
                <div class="w-3 h-3 bg-orange-500 rounded-full mr-2"></div>
                <span>Percentage</span>
            </div>
            <div class="flex items-center">
                <div class="w-3 h-3 bg-green-300 rounded-full mr-2"></div>
                <span>Sales</span>
            </div>
        </div>

    <div class="max-w-sm mx-auto bg-white rounded-lg shadow-md p-4 mt-4">
        <div class="bg-green-100 p-4 rounded-lg flex items-center">
            <div class="w-12 h-12 bg-green-300 rounded-full mr-4"></div>
            <div>
                <h3 class="text-lg font-semibold mb-2">Level up your sales managing to the next level.</h3>
                <p class="text-gray-600 mb-4">An any way to manage sales with care and precision.</p>
                <button class="bg-green-500 text-white py-2 px-4 rounded-lg">Update to Siohioma+</button>
            </div>
        </div>
    </div>
    </div>
    <div class="col-span-2 flex bg-blue-400 flex-row justify-start gap-5 my-10 ">
    <div class="basis-1/2 bg-white rounded-lg shadow p-4">
        <div class="flex justify-between items-center mb-4">
            <h2 class="text-lg font-semibold">Transaction</h2>
            <i class="fas fa-ellipsis-h text-gray-500"></i>
        </div>
        <div class="space-y-4">
            <div class="flex items-center justify-between">
                <div class="flex items-center space-x-4">
                    <div class="bg-gray-200 rounded-full p-2">
                        <i class="fas fa-tshirt text-green-600"></i>
                    </div>
                    <div>
                        <p class="font-medium">Premium T-Shirt</p>
                        <p class="text-sm text-gray-500">Jul 12th 2024</p>
                    </div>
                </div>
                <div class="text-right">
                    <p class="text-green-600 font-medium">Completed</p>
                    <p class="text-sm text-gray-500">0JWEJS7ISNC</p>
                </div>
            </div>
            <div class="flex items-center justify-between">
                <div class="flex items-center space-x-4">
                    <div class="bg-gray-200 rounded-full p-2">
                        <i class="fas fa-gamepad text-gray-600"></i>
                    </div>
                    <div>
                        <p class="font-medium">Playstation 5</p>
                        <p class="text-sm text-gray-500">Jul 12th 2024</p>
                    </div>
                </div>
                <div class="text-right">
                    <p class="text-yellow-600 font-medium">Pending</p>
                    <p class="text-sm text-gray-500">0JWEJS7ISNC</p>
                </div>
            </div>
            <div class="flex items-center justify-between">
                <div class="flex items-center space-x-4">
                    <div class="bg-gray-200 rounded-full p-2">
                        <i class="fas fa-tshirt text-gray-600"></i>
                    </div>
                    <div>
                        <p class="font-medium">Hoodie Gombrong</p>
                        <p class="text-sm text-gray-500">Jul 12th 2024</p>
                    </div>
                </div>
                <div class="text-right">
                    <p class="text-yellow-600 font-medium">Pending</p>
                    <p class="text-sm text-gray-500">0JWEJS7ISNC</p>
                </div>
            </div>
            <div class="flex items-center justify-between">
                <div class="flex items-center space-x-4">
                    <div class="bg-gray-200 rounded-full p-2">
                        <i class="fas fa-mobile-alt text-gray-600"></i>
                    </div>
                    <div>
                        <p class="font-medium">iPhone 15 Pro Max</p>
                        <p class="text-sm text-gray-500">Jul 12th 2024</p>
                    </div>
                </div>
                <div class="text-right">
                    <p class="text-green-600 font-medium">Completed</p>
                    <p class="text-sm text-gray-500">0JWEJS7ISNC</p>
                </div>
            </div>
            <div class="flex items-center justify-between">
                <div class="flex items-center space-x-4">
                    <div class="bg-gray-200 rounded-full p-2">
                        <i class="fas fa-tshirt text-gray-600"></i>
                    </div>
                    <div>
                        <p class="font-medium">Lotse</p>
                        <p class="text-sm text-gray-500">Jul 12th 2024</p>
                    </div>
                </div>
                <div class="text-right">
                    <p class="text-green-600 font-medium">Completed</p>
                    <p class="text-sm text-gray-500">0JWEJS7ISNC</p>
                </div>
            </div>
            <div class="flex items-center justify-between">
                <div class="flex items-center space-x-4">
                    <div class="bg-gray-200 rounded-full p-2">
                        <i class="fas fa-coffee text-gray-600"></i>
                    </div>
                    <div>
                        <p class="font-medium">Starbucks</p>
                        <p class="text-sm text-gray-500">Jul 12th 2024</p>
                    </div>
                </div>
                <div class="text-right">
                    <p class="text-green-600 font-medium">Completed</p>
                    <p class="text-sm text-gray-500">0JWEJS7ISNC</p>
                </div>
            </div>
            <div class="flex items-center justify-between">
                <div class="flex items-center space-x-4">
                    <div class="bg-gray-200 rounded-full p-2">
                        <i class="fas fa-tshirt text-green-600"></i>
                    </div>
                    <div>
                        <p class="font-medium">Tinek Detstar T-Shirt</p>
                        <p class="text-sm text-gray-500">Jul 12th 2024</p>
                    </div>
                </div>
                <div class="text-right">
                    <p class="text-green-600 font-medium">Completed</p>
                    <p class="text-sm text-gray-500">0JWEJS7ISNC</p>
                </div>
            </div>
        </div>
    </div>
    <div class="basis-1/2">
      <!-- Revenue Section -->
      <div class="bg-white p-6 rounded-lg shadow-md mb-6">
        <div class="flex justify-between items-center mb-4">
            <h2 class="text-xl font-semibold">Revenue</h2>
            <div class="flex items-center space-x-2">
                <div class="flex items-center">
                    <div class="w-3 h-3 bg-green-600 rounded-full mr-1"></div>
                    <span class="text-sm">Income</span>
                </div>
                <div class="flex items-center">
                    <div class="w-3 h-3 bg-green-300 rounded-full mr-1"></div>
                    <span class="text-sm">Expenses</span>
                </div>
            </div>
        </div>
        <div class="text-4xl font-bold mb-2">$193.000</div>
        <div class="flex items-center text-green-600 mb-4">
            <i class="fas fa-arrow-up"></i>
            <span class="ml-1">+35% from last month</span>
        </div>
        <div class="flex justify-between items-end h-32">
            <div class="w-1/6 bg-green-600 h-3/4"></div>
            <div class="w-1/6 bg-green-300 h-1/2"></div>
            <div class="w-1/6 bg-green-600 h-4/5"></div>
            <div class="w-1/6 bg-green-300 h-2/5"></div>
            <div class="w-1/6 bg-green-600 h-3/4"></div>
            <div class="w-1/6 bg-green-300 h-1/2"></div>
        </div>
    </div>

    <!-- Sales Report Section -->
    <div class="bg-white p-6 rounded-lg shadow-md">
        <div class="flex justify-between items-center mb-4">
            <h2 class="text-xl font-semibold">Sales Report</h2>
            <i class="fas fa-ellipsis-h text-gray-500"></i>
        </div>
        <div class="space-y-4">
            <div class="flex items-center">
                <div class="bg-green-600 h-6 w-3/4 rounded-l-lg"></div>
                <div class="bg-gray-200 h-6 w-1/4 rounded-r-lg flex items-center justify-end pr-2">
                    <span class="text-sm text-gray-700">Product Launched (233)</span>
                </div>
            </div>
            <div class="flex items-center">
                <div class="bg-green-300 h-6 w-1/4 rounded-l-lg"></div>
                <div class="bg-gray-200 h-6 w-3/4 rounded-r-lg flex items-center justify-end pr-2">
                    <span class="text-sm text-gray-700">Ongoing Product (23)</span>
                </div>
            </div>
            <div class="flex items-center">
                <div class="bg-green-600 h-6 w-full rounded-l-lg"></div>
                <div class="bg-gray-200 h-6 w-0 rounded-r-lg flex items-center justify-end pr-2">
                    <span class="text-sm text-gray-700">Product Sold (482)</span>
                </div>
            </div>
        </div>
    </div>
    </div>
  </div>
  </div>
</template>

<script lang="js">
import SideBar from '@/components/SideBar.vue'

export default {
    components : {
        SideBar
    }
}
</script>
