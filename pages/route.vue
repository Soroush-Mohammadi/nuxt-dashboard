<template>
    <div class="text-xl">
        <span>{{ route.path }}</span><br>
        <span>{{ route.params }}</span><br>
        <span>{{ route.query }}</span><br>
        <button class="bg-yellow-300" @click="getHome">click here</button>
    </div>
</template>


<script setup>



const getHome = () => {
    router.push('/')
}

const store = useStore()
const route = useRoute()
const router = useRouter()
</script>