# Проект на T3 Stack (Next.js, Prisma, NextAuth, TypeScript)

## Описание проекта
Данный проект является клиент-серверным веб-приложением для управления расписанием учебных занятий, что включает в себя просмотр расписания, добавление, удаление и перенос занятий с проверкой на конфликты, поиск свободных аудиторий, создание групп и подгрупп, управление пользователями с разграничением прав доступа.

## Используемые технологии
**T3 Stack (Next.js, TypeScript, Tailwind, tRPC, Prisma, NextAuth)**
- Next.js – React-фреймворк
- TypeScript – строгая типизация
- Prisma – ORM для работы с базой данных
- NextAuth.js – аутентификация
- Tailwind CSS – стилизация

## Установка
1) Клонировать репозиторий

   ``git clone https://github.com/Kuzmenko22/PP_Kursovaya.git``
   
   ``cd PP_Kursovaya``
3) Установить зависимости
   
   ``pnpm install``
5) Инициализация БД
   
   ``pnpm prisma migrate dev --name init``
7) Запуск контейнеров
   
   ``pnpm db:start``
9) Запуск разработки
    
   ``pnpm run dev``

