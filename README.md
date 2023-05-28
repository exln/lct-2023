# Электронный помощник руководителя медицинского учреждения

## Навигация

- [Описание проекта](#desc)
- [Стек технологий](#stack)
- [Сборка проекта](#launch)
- [Документация](#docs)
- [Лицензия](#license)
- [Прототип]()

<a name="desc"></a>

## Описание проекта

Электронный помощник руководителя медицинского учреждения поможет в автоматическом аудите назначений врачей, что позволит контролировать качество оказания медицинских услуг и финансовые расходы учреждения.

<a name="stack"></a>

## Стек технологий

- Frontend:
  [![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)](https://reactjs.org/)
  [![Next](https://img.shields.io/badge/Next-FFF?logo=nextdotjs&logoColor=black)](https://nextjs.org/)
  [![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
- Backend:
  [![C#](https://img.shields.io/badge/C%23-239120?logo=c-sharp&logoColor=white)](https://docs.microsoft.com/en-us/dotnet/csharp/)
  [![.NET](https://img.shields.io/badge/.NET-5C2D91?logo=.net&logoColor=white)](https://docs.microsoft.com/en-us/dotnet/)
  [![Entity Framework Core](https://img.shields.io/badge/Entity_Framework_Core-5C2D91?logo=.net&logoColor=white)](https://docs.microsoft.com/en-us/ef/core/) 
- Database:
  [![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)](https://www.postgresql.org/)
- Parser:
    [![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)](https://www.python.org/)
    [![Selenium](https://img.shields.io/badge/Selenium-43B02A?logo=selenium&logoColor=white)](https://www.selenium.dev/)
- DevOps:
  [![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)](https://www.docker.com/)

<a name="launch"></a>

## Сборка проекта

### Запуск проекта в Docker

1. Установить [Docker](https://www.docker.com/get-started)
2. Склонировать данный репозиторий:
    ```bash
    git clone https://github.com/exln/lct-2023.git lct-exln
    cd lct-exln
    ```
2. Отредактируйте `.env.example` файл и переименуйте его в `.env`:
    ```bash
    cp .env.example .env
    ```
3. Запустите проект с помощью Docker Compose в фоновом режиме:
    ```bash
    docker-compose up -d --build
    ```
4. Теперь приложение доступно по адресу [http://localhost:8080](http://localhost:8080).

<a name="docs"></a>

## Документация

- Документация к решению в формате pdf: [ссылка]()
- Презентация решения: [ссылка]()
- Прототип решения: [ссылка]()

<a name="license"></a>

## Лицензия

![License](https://img.shields.io/github/license/exln/lct-2023?color=blue)

&copy; 2023 **e**x**l**n