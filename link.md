*[< к содержанию](readme.md)*

---

# __ссылки и изображения__ 

- Чтобы создать ссылку с немедленным указанием адреса, надобно немедленно после закрывающей квадратной скобки поместить обычные (круглые) скобки; в этих круглых скобках приводится тот URL, на который указывает гиперссылка, а за ним может ещё быть указан (в кавычках) всплывающий заголовок-подсказка ссылки

  `[пример](http://example.com/ "заголовок")` ссылки с немедленным указанием
адреса.Эта ссылка снабжена всплывающим заголовком-подсказкою.

- Ссылка, подобная сноске, вместо целевого адреса использует вторую пару квадратных скобок, внутри которых помещается метка, идентификатор ссылки:

  `[пример][id]`Затем, где угодно в документе, следует определить эту метку ссылки, для чего используется отдельная строка следующего примерно вида: `[id]: http://example.com/  "А здесь необязательный заголовок ссылки"`

- Для отображения зображения необходимо написать `![Альтернативный текст](/путь/к/изображению.jpg "Необязательное заглавие")`

![котик](/путь/к/изображению.jpg "если изображение не грузится")

или

![Альтернативный текст](cat.jpeg "если изображение грузится")

[больше про котиков](https://ru.wikipedia.org/wiki/%D0%9A%D0%BE%D1%88%D0%BA%D0%B0)