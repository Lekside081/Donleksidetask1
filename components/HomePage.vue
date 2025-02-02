<template>
    <div class="bg-gray-100 min-h-screen p-6">
        <div class="flex justify-between">
      <h1 class="text-3xl font-bold text-gray-800">My Daily Habits</h1>
      <a href="/Blogpost"><p class="text-3xl font-bold">Back</p></a>
      </div>
      <div v-for="habit in habits" :key="habit.id" class="mt-4 p-4 bg-white shadow rounded-lg">
        <p class="text-lg text-gray-700">{{ habit.name }}</p>
        <p class="text-sm text-gray-500">Streak: {{ habit.streak }} days</p>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        habits: [
          { id: 1, name: "Drink Water", streak: 5 },
          { id: 2, name: "Morning Exercise", streak: 10 },
          { id: 3, name: "Read a Book", streak: 3 }
        ]
      };
    }
  };
  </script>
  
  <style scoped>
  </style>
  