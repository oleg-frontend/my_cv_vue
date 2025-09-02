<template>
  <div id="app">
    <Header />
    <div class="main-content">
      <div class="left-side">
        <Experience />
        <Education />
      </div>
      <div class="right-side">
        <Contacts />
        <div class="right-side-content">
          <Skills />
          <Activities />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Experience from './components/Experience.vue'
import Skills from './components/Skills.vue'
import Education from './components/Education.vue'
import Contacts from './components/Contacts.vue'
import Activities from './components/Activities.vue'

export default {
  name: 'App',
  components: {
    Header,
    Experience,
    Skills,
    Education,
    Contacts,
    Activities
  }
}
</script>

<style scoped>
/* Загальні стилі для вашого проєкту */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Arial', sans-serif;
  color: #333;
  line-height: 1.6;
}

#app {
  max-width: 900px;
  margin: 0 auto;
  padding: 20px;
  background: #ffffff; /* Білий фон для основного контейнера */
  border-radius: 12px;
  box-shadow: 0 6px 12px rgba(0, 0, 0, 0.1);
  animation: fadeIn 1.5s ease-out; /* Анімація для появи */
  background: linear-gradient(135deg, #f0f4f8, #e2e9f1); /* Градієнтний фон для контейнера */
}

/* Анімація для всього контенту */
@keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}

.main-content {
  display: flex;
  justify-content: space-between;
  gap: 15px;
  margin-top: 20px;
}

.left-side {
  flex: 1;
}

.right-side {
  width: 250px;
}

section {
  background-color: #fff;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
  margin-bottom: 15px;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  animation: sectionAnimation 0.5s ease-out;
}

section:hover {
  transform: translateY(-5px);
  box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
}

/* Анімація для секцій */
@keyframes sectionAnimation {
  from {
    opacity: 0;
    transform: translateY(20px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

section h2, section h3 {
  font-size: 1.1rem;
  margin-bottom: 8px;
  color: #34495e;
}

section p {
  font-size: 0.9rem;
  color: #7f8c8d;
}

/* Адаптація для мобільних пристроїв */
@media (max-width: 768px) {
  .main-content {
    flex-direction: column;
  }

  .right-side {
    width: 100%;
  }

  .left-side {
    margin-bottom: 20px;
  }

  section {
    padding: 15px;
  }

  section h2, section h3 {
    font-size: 1rem;
  }

  section p {
    font-size: 0.85rem;
  }

  .skills h3 {
    font-size: 1rem;
  }

  .skill p {
    font-size: 0.9rem;
  }

  .stars span {
    font-size: 0.9rem;
  }
}

</style>
