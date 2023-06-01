# Веб-сайт для решения задач по обходу графов

Этот проект представляет собой веб-сайт, разработанный для решения задач, связанных с алгоритмами обхода графов. 
Он предназначен для использования студентами, преподавателями и всеми, кто интересуется данной темой.
Веб-сайт предоставляет возможность проверить правильность решения задач по нахождению остовных деревьев с использованием различных алгоритмов.

## Функциональность

Система поддерживает следующие алгоритмы обхода графов:

- Алгоритм поиска в ширину
- Алгоритм поиска в глубину
- Алгоритм Краскала для нахождения кратчайшего остовного дерева

Каждый из этих алгоритмов может быть выбран пользователем для решения соответствующей задачи.

Главная страница сайта содержит описание функциональности системы и навигационные ссылки для выбора алгоритма решения задачи.

Страница "Об авторах" содержит фотографии разработчиков, их полные имена и краткое описание их личного вклада в проект приложения.

## Технологии

Данный проект реализован с использованием следующих технологий:

- Фреймворк: Bottle
- Язык программирования: Python

Выбор фреймворка Bottle и языка программирования Python обусловлен большим опытом работы команды разработки с ними. Библиотека Bottle обладает удобной системой шаблонов и обработки форм, что значительно упрощает разработку веб-части проекта и задает общую архитектуру приложения.

## Установка и запуск

Для установки и запуска данного веб-сайта необходимо выполнить следующие шаги:

1. Убедитесь, что у вас установлен Python версии 3.x.
2. Клонируйте репозиторий проекта с GitHub:

```bash
git clone https://github.com/pank-su/PR_2.git
```

3. Перейдите в каталог проекта:

```bash
cd PR_2
```

4. Установите необходимые зависимости:

```bash
pip install -r requirements.txt
```

5. Запустите веб-сервер:

```bash
python app.py
```

6. Откройте браузер и перейдите по адресу [http://localhost:5555](http://localhost:5555), чтобы получить доступ к веб-сайту.

## Контрибьюторы

Авторы этого проекта:

- pank_su
  - ФИО: Василий Панков
  - Личный вклад: Создал домашнюю страницу, страницу с авторами и решение алгоритмом Краскала

- Schtimm
  - ФИО: Мерлин Тимофей
  - Личный вклад: Решение поиском в глубину

- Shizik-tech
  - ФИО: Челоноков Алексей
  - Личный вклад: Решение поиском в ширину


## Обратная связь

Если у вас есть вопросы, предложения или сообщения об ошибках, пожалуйста, свяжитесь с нами по адресу pank@pank.su или создайте issue в репозитории проекта на GitHub.

Мы будем рады услышать ваши отзывы и помочь вам в случае возникновения проблем.
