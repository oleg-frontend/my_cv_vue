<template>
  <section class="experience">
    <h2>Досвід роботи</h2>
    <ul>
      <li>
        <strong>Початківець фронтенд-розробник / Фріланс</strong>
        <p>2024 - Теперішній час</p>
        <p>Створення веб-застосунків та сайтів за допомогою Vue.js, HTML, CSS та JavaScript. Верстка адаптивних інтерфейсів та інтерактивних компонентів для портфоліо.</p>
      </li>
      <li>
        <strong>Проекти для портфоліо</strong>
        <p>2023 - 2024</p>
        <p>Розробка невеликих проектів: сайт резюме, гра «Морський бій», «Камінь-ножиці-папір». Вивчення практичного використання компонентів, стану додатків та маршрутизації у Vue.js.</p>
      </li>
      <li>
        <strong>Стажування / Практика</strong>
        <p>2025</p>
        <p>Розробка модального вікна для сайту магазину: форма замовлення, перевірка введених даних та відправка на email. Проект виконано  для знайомого клієнта. Оптимізація коду та інтеграція функціоналу.</p>
      </li>
    </ul>
  </section>
</template>

<script>
export default {
  name: '1Experience'
}
</script>

<style scoped>
.experience {
  background-color: white;
  padding: 30px;
  margin-top: 40px;
  border-radius: 10px;
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
}

.experience h2 {
  font-size: 32px;
  color: #2c3e50;
  margin-bottom: 20px;
  font-weight: 700;
}

.experience ul {
  list-style-type: none;
  padding-left: 0;
}

.experience li {
  margin-bottom: 25px;
  border-bottom: 1px solid #ecf0f1;
  padding-bottom: 20px;
}

.experience strong {
  font-size: 20px;
  color: #4CAF50;
}

.experience p {
  margin: 5px 0;
  font-size: 16px;
  color: #34495e;
}

section {
  padding-left: 20px;
}
</style>
