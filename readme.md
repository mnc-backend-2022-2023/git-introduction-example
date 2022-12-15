# Пример использования git

## Делается 1 раз в начале
1. `git init`
   - инициализация репозитория
1. `git remote add origin git@github.com:mnc-backend-2022-2023/git-introduction-example.git`
   - Объясняю гиту, куда надо грузить код (и откуда скачивать)

## Делается постоянно, когда хотите загрузить свои изменения

1. `git add readme.md` 
   - "включаю наблюдение" за файлом `readme.md`
1. `git commit -m "Мой комментарий"`
   - Сохраняю состояние файлов, за которыми наблюдаю
1. `git push origin main`
   - Отправляю свои изменения на удаленный репозиторий

> Примечание!
> В самый первый раз перед коммитом он может попросить написать
> ваш email и имя и не даст закоммитить

```text
Author identity unknown

*** Please tell me who you are.

Run

git config --global user.email "you@example.com"
git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: empty ident name (for <>) not allowed
```

> Чтобы его исправить, надо, как и написано
> `git config --global user.email "ваш имейл"`
> `git config --global user.name "ваше имя"`

# Домашнее задание

Повторить все шаги описанные здесь внутри своего репозитория
Иметь как минимум 3-4 коммита

Можно использовать такой же файл `readme.md`, код или что бы то ни было еще

## Дополнительные материалы

> Все дополнительные материалы явлюятся необязательными к обучению, но однозначно рекомендуемы
> и полезны для дополнительного освоения

- <https://proglib.io/p/git-for-half-an-hour>
- <https://habr.com/ru/post/541258/>
- Если хочется прям вникнуть, то [(только) вторая глава этой книги](https://git-scm.com/book/ru/v2/%D0%9E%D1%81%D0%BD%D0%BE%D0%B2%D1%8B-Git-%D0%A1%D0%BE%D0%B7%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5-Git-%D1%80%D0%B5%D0%BF%D0%BE%D0%B7%D0%B8%D1%82%D0%BE%D1%80%D0%B8%D1%8F)
- <https://www.youtube.com/watch?v=j2F77U-2FuQ&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=3>
- <https://www.youtube.com/watch?v=zZBiln_2FhM>
- <https://www.youtube.com/watch?v=9d5bJc8o7MA>