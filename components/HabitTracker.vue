<template>
    <div class="bg-gray-900 text-white min-h-screen p-6">
        <div class="flex justify-between">
            <h1 class="text-3xl font-bold">Habit Tracker</h1>
            <a href="/Blogpost"><p class="text-3xl font-bold">Back</p></a>
        </div>
        <p class="mt-2 text-gray-400">Track your progress and streaks over time.</p>

        <div class="mt-6 grid grid-cols-3 gap-4">
            <div v-for="(day, index) in last7Days" :key="index" class="p-4 rounded-lg text-center"
                :class="day.completed ? 'bg-gray-700' : 'bg-gray-500'">
                {{ day.date }}
            </div>
        </div>
    </div>
</template>
  
<script>
export default {
    data() {
        return {
            last7Days: [
                { date: "Jan 24", completed: true },
                { date: "Jan 25", completed: false },
                { date: "Jan 26", completed: true },
                { date: "Jan 27", completed: true },
                { date: "Jan 28", completed: true },
                { date: "Jan 29", completed: false },
                { date: "Jan 30", completed: true }
            ]
        };
    }
};
</script>
  
<style scoped></style>
  