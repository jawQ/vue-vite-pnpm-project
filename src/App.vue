<script setup></script>

<template>
  <div class="app-container">
    <h1 class="app-title">🚀 Vue 3 + Vite + pnpm</h1>
    <p class="app-description">
      Welcome to your awesome Vue.js application! 
      Visit <a href="https://vuejs.org/" target="_blank" rel="noopener">vuejs.org</a> to read the
      documentation
    </p>
    <div class="tech-stack">
      <span class="tech-badge">Vue 3</span>
      <span class="tech-badge">Vite</span>
      <span class="tech-badge">pnpm</span>
    </div>
  </div>
</template>

<style scoped>
.app-container {
  text-align: center;
  padding: 2rem;
  max-width: 800px;
  margin: 0 auto;
}

.app-title {
  color: #42b883;
  font-size: 2.5rem;
  margin-bottom: 1rem;
  font-weight: bold;
}

.app-description {
  font-size: 1.2rem;
  line-height: 1.6;
  color: #666;
  margin-bottom: 2rem;
}

.tech-stack {
  display: flex;
  justify-content: center;
  gap: 1rem;
  flex-wrap: wrap;
}

.tech-badge {
  background: linear-gradient(135deg, #42b883, #35495e);
  color: white;
  padding: 0.5rem 1rem;
  border-radius: 20px;
  font-weight: bold;
  font-size: 0.9rem;
  box-shadow: 0 2px 10px rgba(66, 184, 131, 0.3);
  transition: transform 0.3s ease;
}

.tech-badge:hover {
  transform: translateY(-2px);
}

a {
  color: #42b883;
  text-decoration: none;
  font-weight: bold;
}

a:hover {
  text-decoration: underline;
}
</style>
