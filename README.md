# Dynamic CV

[![Live Demo](https://img.shields.io/badge/demo-live-success)](https://sygrob.netlify.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

A modern, interactive resume website with an editable interface. Built with vanilla JavaScript and Tailwind CSS, this project allows you to create and maintain a professional online CV that can be edited directly in the browser.

## Live Demo

Check out the live version: [https://sygrob.netlify.app/](https://sygrob.netlify.app/)

## Features

- **Interactive Interface** - Clean and professional design with responsive layout
- **Editable Content** - Edit your resume directly in the browser
- **Password Protected** - Secure access to edit mode with password authentication
- **Local Storage** - All changes are saved locally in your browser
- **Fully Responsive** - Works seamlessly on desktop, tablet, and mobile devices
- **Easy to Customize** - Simple HTML/CSS/JS structure for easy modifications

## Technologies

- HTML5
- CSS3 / Tailwind CSS
- Vanilla JavaScript
- Font Awesome Icons
- Google Fonts (Inter)

## Installation & Usage

### Local Setup

1. Clone the repository:

```bash
git clone https://github.com/IvanSnezhok/resume-site.git
cd resume-site
```

2. Open `index.html` in your web browser:

```bash
# Simply open the file in your browser
open index.html
# or
start index.html
```

That's it! No build process or dependencies required.

### How to Edit Your Resume

1. Navigate to the edit mode by adding `?edit=true` to the URL:

   ```
   index.html?edit=true
   ```

   Or if accessing via live site:

   ```
   https://XXXXX.netlify.app/?edit=true
   ```
2. Enter the password when prompted (default password is configured in the JavaScript)
3. Edit your information directly in the interface
4. Click **Save** to store changes in browser's local storage
5. Click **Cancel** to exit without saving changes

### Changing the Password

To change the edit mode password, open `index.html` and modify the `EDIT_PASSWORD` variable:

```javascript
const EDIT_PASSWORD = 'your-new-password-here';
```

## Deployment

This is a static website and can be deployed to any hosting service:

- **Netlify** (recommended)
- GitHub Pages
- Vercel
- Any static hosting service

Simply upload the `index.html` file and you're done!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

Ivan Sniezhok

- GitHub: [@IvanSnezhok](https://github.com/IvanSnezhok)
- LinkedIn: [Ivan Sniezhok](https://www.linkedin.com/in/ivan-snezhok/)

---

# Dynamic CV

[![Демо](https://img.shields.io/badge/%D0%B4%D0%B5%D0%BC%D0%BE-%D0%B6%D0%B8%D0%B2%D0%B5-success)](https://sygrob.netlify.app/)
[![Ліцензія: MIT](https://img.shields.io/badge/%D0%9B%D1%96%D1%86%D0%B5%D0%BD%D0%B7%D1%96%D1%8F-MIT-blue.svg)](https://opensource.org/licenses/MIT)

Сучасний, інтерактивний веб-сайт резюме з можливістю редагування. Створений на vanilla JavaScript та Tailwind CSS, цей проєкт дозволяє створювати та підтримувати професійне онлайн-резюме, яке можна редагувати безпосередньо в браузері.

## Демо

Подивіться живу версію: [https://sygrob.netlify.app/](https://sygrob.netlify.app/)

## Особливості

- **Інтерактивний інтерфейс** - Чистий та професійний дизайн з адаптивною версткою
- **Редагування контенту** - Редагуйте своє резюме безпосередньо в браузері
- **Захист паролем** - Безпечний доступ до режиму редагування з аутентифікацією
- **Локальне збереження** - Всі зміни зберігаються локально у вашому браузері
- **Повна адаптивність** - Бездоганно працює на комп'ютері, планшеті та мобільному
- **Легко налаштовується** - Проста структура HTML/CSS/JS для легкої модифікації

## Технології

- HTML5
- CSS3 / Tailwind CSS
- Vanilla JavaScript
- Font Awesome Icons
- Google Fonts (Inter)

## Встановлення та використання

### Локальне налаштування

1. Клонуйте репозиторій:

```bash
git clone https://github.com/yourusername/resume-site.git
cd resume-site
```

2. Відкрийте `index.html` у вашому веб-браузері:

```bash
# Просто відкрийте файл у браузері
open index.html
# або
start index.html
```

Це все! Не потрібен процес збірки чи залежності.

### Як редагувати своє резюме

1. Перейдіть до режиму редагування, додавши `?edit=true` до URL:

   ```
   index.html?edit=true
   ```

   Або якщо використовуєте live сайт:

   ```
   https://XXXXX.netlify.app/?edit=true
   ```
2. Введіть пароль, коли з'явиться запит (стандартний пароль налаштовано в JavaScript)
3. Редагуйте свою інформацію безпосередньо в інтерфейсі
4. Натисніть **Save** (Зберегти), щоб зберегти зміни в локальному сховищі браузера
5. Натисніть **Cancel** (Скасувати), щоб вийти без збереження змін

### Зміна пароля

Щоб змінити пароль режиму редагування, відкрийте `index.html` і змініть змінну `EDIT_PASSWORD`:

```javascript
const EDIT_PASSWORD = 'ваш-новий-пароль';
```

## Розгортання

Це статичний веб-сайт, який можна розгорнути на будь-якому хостингу:

- **Netlify** (рекомендовано)
- GitHub Pages
- Vercel
- Будь-який статичний хостинг

Просто завантажте файл `index.html` і готово!

## Ліцензія

Цей проєкт ліцензовано під MIT License - див. файл [LICENSE](LICENSE) для деталей.

## Автор

Іван Снєжок

- GitHub: [@IvanSnezhok](https://github.com/IvanSnezhok)
- LinkedIn: [Ivan Sniezhok](https://www.linkedin.com/in/ivan-snezhok/)
