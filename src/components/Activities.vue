<template>
  <section class="activities">
    <h3>Хобі та активності</h3>
    <div class="icons">
      <i class="fas fa-code" title="Програмування"></i>
      <i class="fas fa-gamepad" title="Ігри / Game Development"></i>
      <i class="fas fa-headphones" title="Музика"></i>
      <i class="fas fa-plane" title="Подорожі"></i>
      <i class="fas fa-futbol" title="Спорт / Футбол"></i>
    </div>
  </section>
</template>

<script>
export default {
  name: '1Activities'
}
</script>

<style scoped>
.activities {
  background-color: #fff;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
  margin-bottom: 15px;
  overflow: hidden;
  margin-top: 20px;
}

.activities h3 {
  font-size: 1.4rem;
  color: #2c3e50;
  font-weight: bold;
  margin-bottom: 20px;
  text-align: center;
}

.activities .icons {
  display: flex;
  justify-content: center;
  gap: 15px;
  padding: 0 20px;
}

.activities i {
  font-size: 2rem;
  color: #7f8c8d;
  transition: transform 0.3s ease, color 0.3s ease;
}

.activities i:hover {
  transform: scale(1.2);
  color: #f39c12;
}
</style>
