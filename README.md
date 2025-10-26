# landing_page_base
Настроенный (вроде бы(наверное(не знаю))) проект со svelte для vs code

Че как создано было
Создание проекта:
npx sv create svelte_project

В вопросах выбрать:
- SvelteKit minimal
- Yes, using TypeScript syntax
- Плагины:
1. prettier (formatter - https://prettier.io)
2. eslint (linter - https://eslint.org)
3. vitest (unit testing - https://vitest.dev)
4. playwright (browser testing - https://playwright.dev)
5. tailwindcss (css framework - https://tailwindcss.com)
6. sveltekit-adapter (deployment - https://svelte.dev/docs/kit/adapters)
- vitest: What do you want to use vitest for? unit testing, component testing
-  tailwindcss: Which plugins would you like to add?
1. typography (@tailwindcss/typography)
2. forms (@tailwindcss/forms)
- sveltekit-adapter: auto (пока что)
- Which package manager do you want to install dependencies with? npm

Переключаемся в проект
cd base_svelt_project

Запускаем сервер
npm run dev -- --open
