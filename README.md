# containers_project

## Лабораторные работы

- [Лабораторная работа №1](https://github.com/EgorBodrov/containers_practice_itmo/tree/lab1)

- [Лабораторная работа №2](https://github.com/EgorBodrov/containers_practice_itmo/tree/lab2)

- [Лабораторная работа №3](https://github.com/EgorBodrov/containers_practice_itmo/tree/lab3)

- [Лабораторная работа №4](https://github.com/EgorBodrov/containers_practice_itmo/tree/lab4)

## Описание проекта

Простейший LLM-бот в виде чат-системы для ответа на вопросы про ученых.
Набор данных представляет простейший список фактов о разных людях.
Приложение состоит из следующих частей:
- **agent**. LLM BOT. Для запуска потребуется `OPENAI_API_KEY` и `OPENAI_BASE_URL` в качестве ключа для запуска LLM и прокси сервер.
- **frontend**. Streamlit приложение с чатом
- **backend**. FastApi приложение с пост запросом `commit_question` для ответа на вопрос. Приложения независимо от фронта.
- **qdrant**. Векторное хранилище с эмбеддингами.
