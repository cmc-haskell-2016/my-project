# my-project

[![Build Status](https://travis-ci.org/cmc-haskell-2016/my-project.svg?branch=master)](https://travis-ci.org/cmc-haskell-2016/my-project)

## Установка и запуск

Для установки клонируйте репозиторий и соберите проект с помощью `stack`:

```
git clone https://github.com/cmc-haskell-2016/my-project.git
cd my-project
stack setup
stack build
```

После установки запуск осуществляется командой `stack exec`:

```
stack exec my-project
```

Во время разработки инициировать повторную сборку проекта с последующим запуском рекомендуется
следующей командой:

```
stack build && stack exec my-project
```
