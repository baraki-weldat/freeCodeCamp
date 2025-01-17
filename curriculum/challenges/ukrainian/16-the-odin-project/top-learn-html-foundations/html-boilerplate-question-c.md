---
id: 637f4e2f72c65bc8e73dfe22
title: Шаблонний код HTML. Запитання C
challengeType: 15
dashedName: html-boilerplate-question-c
---

# --description--

В елементі `<head>` розміщується вся важлива метаінформація про вебсторінки, а також все інше, необхідне для правильного відтворення вебсторінок у браузері. Всередині `<head>` не можна використовувати елементи, які показують вміст на сторінці.

## Елемент meta charset
You should always have the `meta` tag for the `charset` encoding of the webpage in the `head` element: `<meta charset="utf-8">`.

Налаштувати кодування символів надзвичайно важливо, оскільки це гарантує, що вебсторінка правильно показуватиме спеціальні символи різних мов.

## Елемент title
Ще одним елементом, який завжди повинен бути в голові документа HTML, є елемент `title`:

```html
<title>My First Webpage</title>
```

Елемент `title` надає вебсторінкам заголовок, який можуть прочитати люди та який показано на вкладці вебсторінки.

Якщо ви не надасте елемент `title`, заголовком вебсторінки за замовчуванням буде назва файлу. У нашому випадку заголовком би був `index.html`, що не дуже змістовно для користувачів. Через це користувачу було б важко найти вебсторінку, якщо відкрито багато вкладок.

У `head` документа HTML можна помістити багато інших елементів. Наразі важливо знати про два елементи, які ми розглянули. Пізніше ви дізнаєтесь про більше елементів, які розміщуються в `head`.

Назад до файлу `index.html`: додайте елемент `head`, який має всередині елемент `meta` `charset` та `title`. Елемент head входить до елемента HTML та завжди повинен бути першим елементом знизу початкового тегу `<html>`:


```html
<!DOCTYPE html>

<html lang="en">
  <head>
    <meta charset="UTF-8">
    <title>My First Webpage</title>
  </head>
</html>
```

# --question--

## --text--

Яка суть елемента `head`?

## --answers--

Елемент `head` використовується для відображення всіх елементів, які відображаються на вебсторінці.

---

Елемент `head` використовується для відображення важливої інформації вебсторінки та правильного відтворення вебсторінок за допомогою елементів `meta`.

---

Елемент `head` використовується для відображення вмісту заголовка у верхній частині вебсторінки.


## --video-solution--

2
