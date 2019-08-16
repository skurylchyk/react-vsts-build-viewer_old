<h1 align="center">React Azure DevOps (VSTS) Build Viewer</h1>

<br>

<div align="center">
  <!-- Package version -->
    <img src="https://img.shields.io/github/package-json/v/BlackPower/react-vsts-build-viewer.svg?longCache=true&style=flat-square"
      alt="Package version" />
  <!-- Last commit -->
    <img src="https://img.shields.io/github/last-commit/BlackPower/react-vsts-build-viewer.svg?longCache=true&style=flat-square"
      alt="Last commit" />
</div>
<br>

### Для запуска проекта выполни следующие шаги

1. [Скачай и установи](https://nodejs.org/en/) последнюю LTS-версию Node.js.
2. Выполни в консоли `node -v` и убедись, что установлена последняя версия Node.js не ниже `v8.11.3`;
3. Введи в консоли `npm -v` и убедись, что установлена последняя версия npm не ниже `5.6.0`;
4. [Скачай и установи Git](https://git-scm.com/downloads), если его нет на компьютере;
5. Введи `git --version`, чтобы проверь версию установленного Git, должно быть не ниже `2.18.0`;
6. Склонируй и запусти этот проект: `git clone https://github.com/BlackPower/react-vsts-build-viewer.git`;
7. Чтобы перейти в директорию с проекта, после клонирования выполни команду `cd react-vsts-build-viewer`;
8. Чтобы установить зависимости проекта, выполни команду `npm install`;
9. Чтобы запустить проект в режиме разработки, самое время выполнить  команду`npm start`;
10. Перейди в браузер и открой страничку [http://localhost:3000](http://localhost:3000/).
11. Открой Chrome Dev Tools и перейди на вкладку Console, там не должно быть каких-либо ошибок.

<br>
<br>

### Краткий обзор команд проекта

> Заметка: запускать через `yarn «имя команды»` или `npm «имя команды»`.

| Команда           | Описание                                                                        |
| ----------------- | ------------------------------------------------------------------------------- |
| `start`           | запустить проект для разработки                                                 |
| `build:prod`      | запустить сборку проекта                                                        |
| `build:analyze`   | запустить сборку проекта и запустить режим детального анализа результата сборки |
| `lint:javascript` | провести анализ исходного JavaScript-кода на стилистические ошибки              |
| `lint:css`        | провести анализ исходного CSS-кода на стилистические ошибки                     |
| `lint`            | провести анализ всего исходного кода на стилистические ошибки                   |
| `test`            | запустить тесты                                                                 |
| `test:watch`      | запустить тесты в watch-режиме                                                  |
| `test:debug`      | запустить тесты в debug-режиме                                                  |
| `soundcheck`      | запустить все линтеры и тесты                                                   |
| `prettier`        | отформатировать исходный код с помощью prettier                                 |
| `deploy`          | задеплоить приложение на свой Github Pages                                      |

> Заметка: после деплоя на Github Pages приложение будет доступно по адресу:\
> https://`имя-твоего-пользователя-гитхаб`.github.io/`имя-твоего-репозитория-с-приложением`
