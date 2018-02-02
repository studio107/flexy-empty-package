[![Build Status](https://travis-ci.org/studio107/flexy-empty-package.svg?branch=master)](https://travis-ci.org/studio107/flexy-empty-package)

* Клонируем репозиторий
* Меняем в package.json "name" (название пакета)
* Складываем в `src` исходники
* В `tests` описываем тесты функций и миксинов. Тесты самих классов не требуются.
* Если есть тесты, то подключаем travis (пример файла .travis.yml.dist)
* Если есть тесты и/или нужно настроить авто деплой в npm, то выполняем `travis npm setup`, ключик от npm берем в `cat ~/.npmrc`
* Перед выгрузкой в npm и пушем в репозиторий выполняем `yarn format` для приведения кода к общему стилю   
