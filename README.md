<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" type="text/css" href="css/Untitled-2.css" />
    <title>Контрольна робота</title>
    <style>
      .contact-info {
        display: flex;
        justify-content: space-between;
        align-items: center;
      }

      .contact-info p {
        display: flex;
        align-items: center;
        margin-bottom: 10px;
      }

      .contact-info p img {
        margin-right: 10px;
      }
    </style>
  </head>
  <body>
    <div class="nav-buttons">
      <button onclick="scrollToSection('about')">Про мене</button>
      <button onclick="scrollToSection('contacts')">Контакти</button>
    </div>

    <section id="about">
      <h2>
        Про мене
        <img
          src="image/photo1688459453.jpeg"
          alt="Гайдаєнко Кирило Студент 1 курсу"
        />
        <p>Гайдаєнко Кирило Студент 1 курсу</p>
      </h2>
      <div class="about-content">
        <p>
          Привіт! Я - починающий розробник з Херсону, Україна. Для мене немає
          жорстких уподобань у виборі фреймворків чи мов програмування. Я
          використовую різні інструменти для кожної задачі. Наразі я навчаюсь в
          університеті, зосереджуючись на вивченні комп'ютерних наук та
          програмування. Мій досвід включає роботу з розробки веб-програм. У
          минулому я використовував Python для створення простих додатків як
          калькулятор, а також вивчаю нову для себе мову С++ для особистих
          проектів.
        </p>
      </div>
    </section>

    <section id="contacts">
      <h2>Контакти</h2>
      <div class="contact-info">
        <div class="contact-block">
          <p>
            <img src="image/1.jpg" alt="Телефон" />
            <a href="tel:+380666910003"> +38(066)6910003|</a>
          </p>
          <p>
            <img src="image/2.png" alt="Email" />
            <a href="tel:+380666910003"> squwkilive@gmail.com|</a>
          </p>
        </div>
        <div class="contact-block">
          <p>
            <img src="image/3.jpg" alt="Instagram" />
            <a href="tel:+380666910003"> Instagram</a>
          </p>
          <p>
            <img src="image/4.png" alt="Discord" />
            Squwiki
          </p>
        </div>
      </div>
    </section>

    <script>
      function scrollToSection(sectionId) {
        const section = document.getElementById(sectionId);
        if (section) {
          section.scrollIntoView({ behavior: "smooth" });
        }
      }
    </script>
  </body>
</html>

img {
  max-width: 10%;
  height: auto;
  display: block;
  margin: 0 auto;
  border-radius: 50%;
}

body {
  margin: 0;
  padding: 0;
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f4f4f4;
  min-height: 200vh;
  background-image: url("C:/Сайтик/image/Photo.jpg");
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 20px;
}

header {
  background-color: #333;
  color: #fff;
  text-align: center;
  padding: 1em 0;
  height: 100px;
}

section {
  max-width: 800px;
  margin: 20px auto;
  padding: 20px;
  background-color: #fff;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

h2 {
  margin-bottom: 30px; /* Зменшено відступ заголовка */
  text-align: center;
}

p {
  margin-bottom: 5px; /* Зменшено відступ звичайного тексту */
  font-size: 16px; /* Збільшено розмір звичайного тексту */
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  margin-bottom: 20px; /* Зменшено відступ списку */
}

footer {
  background-color: #333;
  color: #fff;
  text-align: center;
  padding: 1em 0;
  width: 50%;
  height: 20px;
}

.nav-buttons {
  text-align: center;
  margin-bottom: 20px;
}

.nav-buttons button {
  background-color: #d4b609;
  color: #fff;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  transition: background-color 0.3s;
  margin-right: 10px;
}

.nav-buttons button:hover {
  background-color: #d4b609;
}

.contact-info {
  display: flex;
  justify-content: space-between;
  width: 100%;
}

.contact-info p {
  cursor: pointer; /* Робимо текст клікабельним */
  color: #007bff; /* Задаємо колір посилань */
}

.contact-info p:hover {
  text-decoration: underline; /* Додаємо підкреслення при наведенні */
}
