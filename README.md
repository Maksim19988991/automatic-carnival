# (replace-me: Exercise title)

_(replace-me: One-line description of the exercise)_

## Welcome

- **Who is this for**: (replace-me: Target audience description)
- **What you'll learn**: (replace-me: Learning objectives)
- **What you'll build**: (replace-me: Description of what the learner will create)
- **Prerequisites**:
  - (replace-me: Prerequisite skill/exercise)
  - (replace-me: Other prerequisites)

- **How long**: This exercise takes less than (replace-me: estimated time) to complete.

In this exercise, you will:

1. (replace-me: Learning objective step #1)
1. (replace-me: Learning objective step #2)
1. (replace-me: Learning objective step #N)


### How to start this exercise

Simply copy the exercise to your account, then give your favorite Octocat (Mona) **about 20 seconds** to prepare the first lesson, then **refresh the page**.

<!--  (replace-me: Make sure to edit the URL with proper template_owner, template_name, repo name and description)  -->
[![](https://img.shields.io/badge/Copy%20Exercise-%E2%86%92-1f883d?style=for-the-badge&logo=github&labelColor=197935)](https://github.com/new?template_owner=skills&template_name=exercise-template&owner=%40me&name=skills-<replace-me>&description=Exercise:+Replace+me&visibility=public)
]]]
<details>
<summary>Having trouble? 🤷</summary><br/>

When copying the exercise, we recommend the following settings:

- For owner, choose your personal account or an organization to host the repository.

- We recommend creating a public repository, since private repositories will use Actions minutes.

If the exercise isn't ready in 20 seconds, please check the [Actions](../../actions) tab.

- Check to see if a job is running. Sometimes it simply takes a bit longer.

- If the page shows a failed job, please submit an issue. Nice, you found a bug! 🐛

</details>

---

&copy; 2025 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)
Звісно! Ось оновлений приклад головної сторінки сайту "Теремок" у чорних і бежевих кольорах з використанням CSS для стилізації. Це базовий шаблон, який можна доповнювати і розширювати.

Оновлений код HTML + CSS для сайту "Теремок" у чорно-бежевих кольорах






Теремок - Дропшиппинг сайт

  /* Основні стилі */
  body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #111; /* Темний фон */
    color: #f5deb3; /* Бежевий текст */
  }

  /* Шапка */
  header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 30px;
    background-color: #222; /* Темно-чорний фон шапки */
    border-bottom: 2px solid #555;
  }

  .logo {
    font-size: 24px;
    font-weight: bold;
    color: #f5deb3; /* Бежевий логотип */
  }

  nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
  }

  nav ul li {
    margin-left: 20px;
  }

  nav ul li a {
    color: #f5deb3;
    text-decoration: none;
    font-weight: 600;
    transition: color 0.3s;
  }

  nav ul li a:hover {
    color: #ffe4b5; /* Світліший відтінок при наведенні */
  }

  .search-cart {
    display: flex;
    align-items: center;
  }

  .search-cart input {
    padding: 8px 12px;
    border: none;
    border-radius: 4px;
    outline: none;
    font-family: Arial, sans-serif;
  }

  .cart-icon {
    margin-left: 15px;
    font-size: 20px;
    cursor: pointer;
    color: #f5deb3;
  }

  /* Основний контент */
  main {
    padding: 20px;
  }

  /* Банер */
  .banner {
    background-color: #333;
    color: #f5deb3;
    padding: 40px 20px;
    text-align: center;
    border-radius: 8px;
    margin-bottom: 30px;
  }

  .banner h1 {
    font-size: 32px;
    margin-bottom: 20px;
  }

  .btn {
    display: inline-block;
    padding: 12px 24px;
    background-color: #f5deb3;
    color: #111;
    font-weight: bold;
    text-decoration: none;
    border-radius: 4px;
    transition: background-color 0.3s;
  }

  .btn:hover {
    background-color: #ffe4b5;
  }

  /* Категорії */
  .categories {
    margin-bottom: 30px;
  }

  .categories h2 {
    color: #f5deb3;
    margin-bottom: 15px;
  }

  .category-list {
    display: flex;
    gap: 15px;
    flex-wrap: wrap;
  }

  .category {
    background-color: #222;
    padding: 15px;
    border-radius: 8px;
    cursor: pointer;
    flex: 1 1 calc(25% - 20px);
    text-align: center;
    transition: background-color 0.3s;
  }

  .category:hover {
    background-color: #444;
  }

  /* Товари */
  .products {
    margin-bottom: 30px;
  }

  .products h2 {
    color: #f5deb3;
    margin-bottom: 15px;
  }

  .product-grid {
    display: flex;
    gap: 20px;
    flex-wrap: wrap;
  }

  .product-card {
    background-color: #222;
    padding: 15px;
    border-radius: 8px;
    width: calc(25% - 20px);
    box-shadow: 0 0 10px rgba(0,0,0,0.5);
    transition: transform 0.3s, box-shadow 0.3s;
  }

  .product-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 0 15px rgba(0,0,0,0.7);
  }

  .product-card img {
    width: 100%;
    border-radius: 4px;
    margin-bottom: 10px;
  }

  .product-card h3 {
    margin: 10px 0 5px;
    font-size: 16px;
  }

  .product-card p {
    margin: 5px 0 10px;
    font-weight: bold;
  }

  .product-card button {
    background-color: #f5deb3;
    color: #111;
    border: none;
    padding: 10px;
    width: 100%;
    border-radius: 4px;
    font-weight: bold;
    cursor: pointer;
    transition: background-color 0.3s;
  }

  .product-card button:hover {
    background-color: #ffe4b5;
  }

  /* Футер */
  footer {
    background-color: #222;
    padding: 20px;
    text-align: center;
    color: #f5deb3;
  }

  .social a {
    color: #f5deb3;
    margin: 0 10px;
    text-decoration: none;
  }

  .social a:hover {
    color: #ffe4b5;
  }

  /* Адаптивність */
  @media(max-width: 1024px) {
    .category {
      flex: 1 1 calc(50% - 20px);
    }

    .product-card {
      width: calc(50% - 20px);
    }
  }

  @media(max-width: 600px) {
    header {
      flex-direction: column;
      align-items: flex-start;
    }

    nav ul {
      flex-direction: column;
    }

    .category, .product-card {
      width: 100%;
    }
  }




  Теремок

      Головна
      Категорії
      Акції
      Про нас
      Контакти

    🛒 0

    Вигідні пропозиції в "Теремок"
    Переглянути всі

    Категорії

      Електроніка
      Побутова техніка
      Товари для дому
      Дитячі товари

    Новинки

        Назва товару 1
        Ціна: 1000 грн
        Купити

        Назва товару 2
        Ціна: 2000 грн
        Купити


  &copy; 2025 Теремок. Всі права захищені.

    Facebook | Instagram | Telegram
