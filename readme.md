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
> ```text
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
