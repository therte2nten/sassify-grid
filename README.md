![Изображение-баннер с логотипом проекта Sassify и логотипом GitHub](https://github.com/therteenten/sassify/blob/main/.github/images/sassify_banner_github.png?raw=true)

<img src="https://github.com/therteenten/sassify-grid/blob/main/.github/images/sassify-grid_logo.png?raw=true" width="96" height="96" align="right" alt="Логотип проекта Sassify Grid"> [Sassify Grid](https://github.com/therteenten/sassify-grid.git)
===

Простая реализация 12-ти колоночной Grid System из Bootstrap на языке CSS-препроцессора Sass.

![Список языков](https://img.shields.io/github/languages/count/therteenten/sassify-grid?color=%23ff0056)
![Топ язык в репо](https://img.shields.io/github/languages/top/therteenten/sassify-grid?color=%23ff0056)
![Кол-во открытых ишью](https://img.shields.io/github/issues-raw/therteenten/sassify-grid)
![Кол-во открытых PR](https://img.shields.io/github/issues-pr-raw/therteenten/sassify-grid)
![Лицензия](https://img.shields.io/github/license/therteenten/sassify-grid)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/therteenten/sassify-grid)
![GitHub contributors](https://img.shields.io/github/contributors/therteenten/sassify-grid)
![GitHub last commit](https://img.shields.io/github/last-commit/therteenten/sassify-grid)


## Быстрый старт
1. Перед тем как начать нужно удостовериться в том, что у Вас установлен Node.js:

	```sh
	node -v
	# или
	npm -v
	```
	```sh
	v16.18.1
	# или
	9.6.4
	```

	> Если у Вас какая-то другая версия - всё нормально. Значит Node.js у Вас установлен.

2. Далее с помощью пакетного менеджера для Node.js устанавливаем пакет в ваш проект:

	```sh
	# npm
	npm install @therteenten/sassify-grid --save-dev
	```
	```sh
	# Yarn
	yarn add @therteenten/sassify-grid --dev
	```
	```sh
	# pnpm
	pnpm install @therteenten/sassify-grid -D
	```

3. Далее в нужный Sass/SCSS-файл импортируем модуль sassify-grid:

	```scss
	@use 'node_modules/@therteenten/sassify-grid' as grid;
	```

	> Если Вы до сих пор используете директиву `@import` в Sass, то вот что говорят разработчики Sass в своем блоге:
	>
	> > The Sass team wants to allow for a large amount of time when `@use` and `@import` can coexist, to help the ecosystem smoothly migrate to the new system. However, doing away with `@import` entirely is the ultimate goal for simplicity, performance, and CSS compatibility.
	> > <details><summary>Перевод (машинный)</summary><br><p>Команда Sass хочет предусмотреть большое количество времени, когда <code>@use</code>  и <code>@import</code> могут сосуществовать, чтобы помочь экосистеме плавно перейти на новую систему. Однако полный отказ от <code>@import</code> является конечной целью для простоты, производительности и совместимости с CSS.</p></details>

4. **Готово!**

## Сообщество
У проекта sassify-grid нет какого-либо сервера в Discord и нет своего канала или чата в Telegram или где-либо еще.

Все основные новости по проекту публикуются в личном Telegram-канале автора проекта - [@therte2nten][sassify-grid-telegram] (там же есть и чат).

## Версии
Sassify Grid основан на реализации сетки из [Bootstrap][github-repo-bootstrap] и версии Sassify Grid называются в соответствии с версией Bootstrap, из которой была взята реализация сетки.

Например Sassify Grid v3.3.6 соответствует реализации сетки из Bootstrap v3.3.6.

## Благодарности

- разработчикам [Bootstrap][github-repo-bootstrap] - за сетку Bootstrap Grid,
- разработчикам CSS-препроцессора [Sass][sass-site] - за непосредственно Sass.

## Лицензия
Проект распространяется по свободной лицензии MIT, однако в проекте используются труды иных людей, чьё авторство я также обозначил в местах, где используется их код.

```
MIT License

Copyright (c) 2011-2023 The Bootstrap Authors
Copyright (c) 2023 Haba Kudzaev <therteenten@inbox.ru>
```

> Если Вы нашли нарушение чьей-либо лицензии в моем проекте, то просьба написать мне → [Telegram][therteenten-telegram], [эл. почта][therteenten-email] или [VK][therteenten-vk].

<!-- ! -->
[sass-site]: https://sass-lang.com/
[github-repo-bootstrap]: https://github.com/twbs/bootstrap
[sassdoc-site]: http://sassdoc.com/
[sassify-grid-telegram]: https://t.me/therte2nten
[therteenten-vk]: https://vk.com/therteenten
[therteenten-telegram]: https://t.me/therteenten
[therteenten-email]: mailto:therteenten@inbox.ru
<!-- ! -->
