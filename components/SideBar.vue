<template>
<div class="flex">
  <!-- Sidebar -->
  <div class="bg-green-900 text-white w-64 h-screen flex flex-col justify-between">
   <div>
    <!-- Logo -->
    <div class="p-6">
     <h1 class="text-2xl font-bold">
      Siohioma
     </h1>
    </div>
    <!-- Menu -->
    <nav class="px-6">
     <h2 class="text-sm font-semibold mb-4">
      MENU
     </h2>
     <ul>
      <li class="mb-4" v-for="item in menuItems" :key=item.id>
       <a class="flex items-center text-green-300" href="#">
        <i class="fas fa-home mr-3">
        </i>
        {{ item.name}}
       </a>
      </li>
     </ul>
     <h2 class="text-sm font-semibold mt-8 mb-4">
      GENERAL
     </h2>
     <ul>
      <li class="mb-4" v-for='item in generalItems' :key="item.id">
       <a class="flex items-center" href="#">
        <i class="fas fa-cog mr-3">
        </i>
        {{ item.name }}
       </a>
      </li>
     
     </ul>
    </nav>
   </div>
   <!-- User Info -->
   <div class="p-6 bg-green-800">
    <div class="flex items-center">
     <img alt="User avatar" class="rounded-full mr-3" height="40" :src="`/${user.avatar}`" width="40"/>
     <div>
      <p class="font-semibold">
       {{ user.username }}
      </p>
      <p class="text-sm text-green-300">
        {{  user.email }}
      </p>
     </div>
    </div>
   </div>
  </div>
  <!-- Main Content -->
  <div class="flex-1 p-6">
   <!-- Add your main content here -->
  </div>
 </div>

</template>

<script setup>
const menuItems = [
  { name : 'OverView', icon : '', id : 'kdj'},
  { name : 'Statics', icon : '', id : 'gtr'},
  { name : 'Product', icon : '', id : 'mkf'},
  { name : 'Transactions', icon : '', id : 'der'},
  { name : 'OverView', icon : '', id : 'dcs'},
]

const generalItems = [
  {
    name : 'Settings',
    icon : '',
    id : 'flt'
  },
  {
    name : 'Security',
    icon : '',
    id : 'rec'
  }
];

const user = {
  username : 'CodePuse',
  email : 'CodePuse@gmail.com',
  avatar : 'avatar.jpg'
}

</script>