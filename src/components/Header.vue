<template>
    <header class = "flex flex-col w-full container">
      <Title msg = "🚀 Kaylas App 🚀" />
      <NewTodo />
    </header>
</template>

<script setup>
import Title from './Titles.vue'
import NewTodo from './NewTodo.vue'
</script>