<template>
  <div>
    <h1>Blog Posts</h1>
    <ul v-if="posts">
      <li v-for="post in posts" :key="post.id">{{ post.title }}</li>
    </ul>
  </div>
</template>

<script setup>
import { ref } from 'vue'

const posts = ref([]) // Reactive reference for posts
const error = ref(null) // Reactive reference for error handling

// Fetch posts directly using useFetch
const { data, error: fetchError } = await useFetch("http://localhost:5000/api/posts");
posts.value = data.value
// Assign data and handle errors

</script>
