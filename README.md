#  GraphQL

**GraphQL** имеет три основные характеристики:
- Он позволяет клиенту точно указать, какие данные ему нужны.
- Облегчает агрегацию данных из нескольких источников.
- Использует систему типов для описания данных.

## Полезные ссылки:
- [Graphql (Документация)](https://graphql.org/learn/)

## Установка зависимостей:
- Для сервера: `npm i express nodemon graphql express-graphql mongoose cors --save`
- Для приложения (UI): `yarn add apollo-boost react-apollo graphql @material-ui/core @material-ui/icons react-swipeable-views recompose`

## Быстрый старт серверной части:
- Клонируйте репозиторий: `git clone https://github.com/YauhenKavalchuk/graphql-tutorial.git`
- Перейдите в папку **server** и установите зависимости: `npm install`
- Запустите проект: `npm run dev`

## Быстрый старт приложения:
- Клонируйте репозиторий: `git clone https://github.com/YauhenKavalchuk/graphql-tutorial.git`
-  Перейдите в нужную ветку соответствующую уроку: `git checkout lesson_10` или `git lesson_11` и т.д.
- Перейдите в папку **server** и установите зависимости: `npm install`
	- Запустите сервер: `npm run dev`
- Перейдите в папку **application** и установите зависимости: `yarn install`
	- Запустите проект: `yarn start`
