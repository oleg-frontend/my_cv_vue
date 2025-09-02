<template>
  <section class="education">
    <h2>Освіта</h2>
    <ul>
      <li>
        <strong>Кам'янець-Подільський фаховий коледж харчової промисловості НУХТ</strong> — Комп’ютерні науки, 2019–2023
      </li>
      <li>
        <strong>Курси з фронтенд-розробки</strong> — Stfalcon, 2025
      </li>
      <li>
        <strong>Базовий курс з веб-розробки</strong> — Self-study, 2024
      </li>
    </ul>
  </section>
</template>

<script>
export default {
  name: '1Education'
}
</script>

<style scoped>
.education {
  background-color: white;
  padding: 30px;
  margin-top: 40px;
  border-radius: 10px;
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
}

.education h2 {
  font-size: 32px;
  color: #2c3e50;
  margin-bottom: 20px;
  font-weight: 700;
}

.education ul {
  list-style-type: none;
  padding-left: 0;
}

.education li {
  margin-bottom: 20px;
}

.education strong {
  font-size: 20px;
  color: #4CAF50;
}
</style>
