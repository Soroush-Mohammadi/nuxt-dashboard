<template>
  <ul>
    <div>
      <h2>{{ title }}</h2>
    </div>
    <li v-for="user in users" :key="user.id">
      <span> Name : </span>
      <h6>
        {{ user.name }}
      </h6>
    </li>
  </ul>
</template>

<script setup>
const { data: users, error } = await useAsyncData("users", () =>
  $fetch("http://localhost:5000/api/users")
);

const title = ref("Users Title");
useHead({ title: title });
</script>
