---
title: "Шпаргалка про то как писать посты"
date: 2023-02-18T23:29:21Z
draft: true
github_link:
image: ""
description: ""
toc: true
tags:
  - Markdown syntax
  - example
---

## Это заголовок. Здесь мы будем вставлять картинки

Картинку мы положим в папку с постом.

{{< figure src="profile.png" caption="Заголовок картинки" >}}

Можно делать картинку и без подписи и даже задать ее размеры для отображения предпросмотра.

{{< figure src="profile.png" width="100%" height="100%" >}}

Можно сделать галерею из картинок в обычном посте. Для этого нужно сделать папку внутри папки поста и положить туда картинки. Например, здесь мы сделали папку img и положили туда картинки.

{{< gallery album="img" >}}

Можно конечно и совсем тупо картинку вставлять, но тогда она не будет вписываться на страницу

![profile](profile2.jpg)

### Заголовок уровнем пониже. Простое форматирование текста

Здесь мы посмотрим как можно оформлять текст.

Можно сделать текст **жирным** или *курсивным*. Текст курсивом можно делать и _вот таким образом_. Это может пригодиться, чтобы сделать _**жирный курсив**_. Ну а можно просто хреначить по ***три звездочки*** или ___три подчеркивания___.

Некоторая проблема может быть с подчеркнутым текстом - для этого придется <ins>использовать теги</ins>

Для зачеркнутого текста мы используем ~~символ тильды~~

Для программистов может быть полезно выделять `моноширинный текст`.

И моноширинный текст из нескольких строк (можно даже добавить подсветку синтаксиса, если указать язык)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Example HTML5 Document</title>
  </head>
  <body>
    <p>Test</p>
  </body>
</html>
```

### Продвинутое оформление текста.

> Текст можно формлять в виде цитаты. Он будет выделен специальным блоком, отступом и полосочкой.
> Цитаты могут быть и многострочными
>
> И даже многоабзацными
>
> — <cite>И даже автора цитаты добавить</cite>

Ненумерованные списки просто пишутся с новой строки о отделяются дефисами
- вот так
- вот так вот
- вот так вот так

На самом деле можно делать и многоуровневые списки просто добавляя отступ с помощью клавиши tab
- звезда
- еще звезда
    - внутренний элемент могоуровнвого списка
      - как угодно глубоко


Нумерованные списки делаются просто цифрами

1. Первый
2. Второй
3. Третий

А еще есть списки с чекбоксами

- [ ] Вариант 1
- [x] Вариант 2 отмечен
- [ ] Вариант 3

Еще интересная возможность делать сноски[^1]. Само описание сноски будет показано внизу страницы вне зависимости от того, где написано описание.

[^1]: The above quote is excerpted from Rob Pike's [talk](https://www.youtube.com/watch?v=PAAkCSZUG1c) during Gopherfest, November 18, 2015.

Ссылки на какие-то внешние ресурсы можно ставить так название ссылки в квадратных скобках, а сама ссылка в круглых [google](https://www.google.com/)

Остальные штуки можно посмотреть в файле `markdown-sintax.md`.

Ну или [здесь](https://dillinger.io/)