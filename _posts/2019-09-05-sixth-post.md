--- 
layout: post
title: Просто информативный пост
description: This is a post with an introduction image and text
intro: Просто тестовый пост с текстом и картинкой!
intro_image: /img/metallica.jpg
intro_image_ratio: is-16by9
---

Версия 0.3 позволяет вам предоставить вступление  и вступительную картинку. При создании поста, добавьте короткий `intro` текст и `intro_image` в качестве пути к изображению, а затем укажите `intro_image_ratio`, которая должна быть [Bulma image](https://bulma.io/documentation/elements/image/) class. 

```yaml
layout: post
title: Просто информативный пост
intro: Просто тестовый пост с текстом и картинкой!
intro_image: /img/metallica.jpg
intro_image_ratio: is-16by9
```

Необходимо только вступление, если вы хотите отобразить его. Если вам не нужна картинка, просто не указывайте её, и будет отображаться только вступительный текст :)