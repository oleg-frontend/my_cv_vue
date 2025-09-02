<template>
  <header class="header">
    <div class="header-content">
      <div class="header-text">
        <h1>Олег Шмирко</h1>
        <p>Початківець фронтенд-розробник</p>
        <p>Створюю веб-застосунки та сайти з використанням Vue.js, HTML, CSS і JavaScript. Маю досвід у верстці, компонентах та інтерактивних проектах для портфоліо.</p>
      </div>
      <img src="@/assets/photo.jpg" alt="Фото" class="photo" />
    </div>
  </header>
</template>

<script>
export default {
  name: '1Header'
}
</script>


<style scoped>
.header {
  background-color: #2c3e50;
  color: white;
  padding: 60px 0;
  text-align: center;
}

.header-content {
  display: flex;
  justify-content: center;
  align-items: center;
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 20px;
}

.header-text {
  max-width: 600px;
  margin-right: 40px;
}

.header-text h1 {
  font-size: 40px;
  font-weight: bold;
  margin-bottom: 10px;
}

.header-text p {
  font-size: 18px;
  margin: 8px 0;
}

.header-text a {
  color: #ecf0f1;
  text-decoration: none;
}

.header-text a:hover {
  text-decoration: underline;
}

.photo {
  border-radius: 50%;
  width: 150px;
  height: 150px;
  object-fit: cover;
  box-shadow: 0 0 15px rgba(0, 0, 0, 0.2);
}


@media (max-width: 768px) {
  .header-content {
    flex-direction: column-reverse;
    text-align: center;
  }

  .header-text {
    margin-right: 0;
    margin-top: 20px;
  }

  .photo {
    margin-bottom: 20px;
  }
}
</style>
