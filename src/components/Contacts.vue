<template>
  <section class="contacts">
    <h2>Контакти</h2>
    <p>Телефон: <a href="tel:+380636933290">+380636933290</a></p>
    <p>Email: <a href="mailto:oleh.shmyrko@gmail.com">oleh.shmyrko@gmail.com</a></p>
    <p>Місто: Хмельницький</p>
    <div class="social-icons">
      <a href="https://www.linkedin.com/in/oleh-shmyrko-0a176b348" target="_blank" class="social-icon" title="LinkedIn">
        <i class="fab fa-linkedin"></i>
      </a>
      <a href="https://github.com/oleg-frontend" target="_blank" class="social-icon" title="GitHub">
        <i class="fab fa-github"></i>
      </a>
      <a href="https://www.instagram.com/molodoy_4elove4ekk_/" target="_blank" class="social-icon" title="Instagram">
        <i class="fab fa-instagram"></i>
      </a>
    </div>
  </section>
</template>

<script>
export default {
  name: '1Contacts'
}
</script>

<style scoped>
.contacts {
  background-color: #fff;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
}

.contacts h2 {
  font-size: 1.5rem;
  margin-bottom: 15px;
  color: #2c3e50;
}

.contacts p {
  font-size: 1rem;
  color: #7f8c8d;
}

.contacts a {
  color: #2980b9;
  text-decoration: none;
}

.contacts a:hover {
  text-decoration: underline;
  cursor: pointer;
}

.social-icons {
  display: flex;
  gap: 15px;
  margin-top: 10px;
}

.social-icon i {
  font-size: 1.5rem;
  color: #34495e;
  transition: color 0.3s ease, transform 0.3s ease;
}

.social-icon:hover i {
  color: #f39c12;
  transform: scale(1.1);
}

.social-icon[title]:hover:after {
  content: attr(title);
  position: absolute;
  top: -25px;
  left: 50%;
  transform: translateX(-50%);
  background-color: #2c3e50;
  color: #fff;
  padding: 5px 10px;
  font-size: 0.85rem;
  border-radius: 4px;
  white-space: nowrap;
}
</style>
