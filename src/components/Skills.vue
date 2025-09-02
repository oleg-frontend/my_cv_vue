<template>
  <section class="skills">
    <h2>Навички</h2>
    <div class="skill">
      <p>HTML</p>
      <div class="stars">
        <span v-for="n in 5" :key="n" :class="{'filled': n <= 4}">★</span>
      </div>
    </div>
    <div class="skill">
      <p>CSS</p>
      <div class="stars">
        <span v-for="n in 5" :key="n" :class="{'filled': n <= 4}">★</span>
      </div>
    </div>
    <div class="skill">
      <p>JavaScript</p>
      <div class="stars">
        <span v-for="n in 5" :key="n" :class="{'filled': n <= 4}">★</span>
      </div>
    </div>
    <div class="skill">
      <p>Vue.js</p>
      <div class="stars">
        <span v-for="n in 5" :key="n" :class="{'filled': n <= 4}">★</span>
      </div>
    </div>
    <div class="skill">
      <p>Git / GitHub</p>
      <div class="stars">
        <span v-for="n in 5" :key="n" :class="{'filled': n <= 3}">★</span>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: '1Skills'
}
</script>

<style scoped>
.skills h2 {
  font-size: 1.5rem;
  color: #2c3e50;
  margin-bottom: 8px;
  font-weight: 700;
  padding-left: 12px;
}

.skill {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding-left: 10px;
  padding-right: 10px;
  margin-bottom: 5px;
}

.skill p {
  font-family: 'Arial', sans-serif;
  font-size: 0.9rem;
  color: #2c3e50;
  margin: 0;
}

.stars {
  display: flex;
  gap: 2px;
}

.stars span {
  font-size: 1rem;
  color: #ccc;
}

.stars .filled {
  color: #f39c12;
}

.skills {
  padding: 10px;
  margin-bottom: 0;
  font-size: 0.85rem;
}
</style>
