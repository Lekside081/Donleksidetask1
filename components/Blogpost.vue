<template>
    <div class="mt-2 mb-4">
        <h1 class="text-red-400 text-2xl"># My HNG12 Journey and Sonder App Design</h1>
        <div class="text-xl mt-2">Starting HNG12 has been an exciting journey. My main goals for this internship include:</div>

        <p class="text-xl mt-2">- Mastering **UI/UX Design** principles.</p>
        <p class="text-xl">- Contributing to real-world projects.</p>
        <p class="text-xl">- Building a strong **portfolio**.</p>

        <h1 class="text-red-400 text-2xl mt-2">## Sonder App Design Process</h1>
        <div class="text-xl mt-2">I designed **two screens**:</div>

        <p class="text-xl mt-2">✅ **Home page** - User interact with their habits.</p>
        <p class="text-xl">✅ **Habit Tracker** - Show progress & streaks</p>
        <p class="text-xl">✅ **Achromatic Color Palette** – Clean black, white, and gray tones</p>
        
        <h1 class="text-red-400 text-2xl mt-2">### **Screenshots of My Design** </h1>
        <div class="mt-2">
            <a href="/My daily habit.PNG"><p>[<span class="text-green-600">{{ name }}</span>] (<span class="text-blue-600 underline">{{ title }})</span></p></a>
            <div class="basis-1/2 py-16">
                <img :src="img">
            </div>
            <a href="/My Habit tracker.PNG"><p>[<span class="text-green-600">Habit Tracker</span>] (<span class="text-blue-600 underline">path to tracker screen.png)</span></p></a>
            <div class="basis-1/2 py-16">
                <img :src="img2">
            </div>

            <div class="mt-2">
                <p class="text-red-400">This Link to website Code Below</p>
                <a href="/HomePage"><p>[<span class="text-green-600">Home Page</span>] (<span class="text-blue-600 underline">Path to Home screen)</span></p></a>
            <a href="/HabitTracker"><p>[<span class="text-green-600">Habit Tracker</span>] (<span class="text-blue-600 underline">path to tracker screen)</span></p></a>
            </div>
        </div>

        <h1 class="text-red-400 text-2xl mt-2">## 💻 Tech Stack</h1>
        <div class="text-xl mt-2">I built this project using:</div>
        <div class="text-xl">🔹 **Vue 3** – Component-based UI framework</div>
        <div class="text-xl">🔹 **Tailwind CSS** – Fast, responsive styling</div>
        <div class="text-xl">🔹 **GitHub** – Code versioning & collaboration</div>
        <div class="text-xl mt-2">🔗 **View My GitHub Repo**: [<span class="text-green-400">GitHub Link Here</span>](https://github.com/your-repo-link)</div>

        <h1 class="text-red-400 text-2xl mt-2">## **Want to Hire a Skilled UI Designer?**</h1>
        <div class="text-xl mt-2">Check out HNG’s talented designers here:</div>
        <p>[<span class="text-green-600">Hire a UI Designer</span>] (<span class="text-blue-600 underline">https://hng.tech/hire/ui-designers)</span></p>
    </div>
</template>

<script setup>
defineProps(
   ['name', 'title', 'img', 'img2']
)

</script>