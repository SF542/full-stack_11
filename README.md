# Задание №11. AMP-версия Gustoso

- [Исходная страница](https://sf542.github.io/full-stack_11/)
- [AMP-версия](https://sf542.github.io/full-stack_11/amp.html)

AMP-версия сделана на основе вёрстки задания №4. Стили добавлены в `style amp-custom`, изображения переведены на `amp-img`. Меню и галерея работают через `amp-bind`, окна завтрака и рецепта открываются через `amp-lightbox`. В исходной версии сохранилась загрузка Less в браузере.

Опубликованная AMP-страница прошла проверку AMP Validator с результатом `PASS`.

## Сравнение в PageSpeed Insights

Замеры сделаны 23 ноября 2026 года. В таблице приведены лабораторные результаты Lighthouse из PageSpeed Insights. Данных о реальных посещениях страниц в Chrome UX Report пока недостаточно.

| Показатель | [Оригинал, телефон][original-mobile] | [AMP, телефон][amp-mobile] | [Оригинал, компьютер][original-desktop] | [AMP, компьютер][amp-desktop] |
| --- | ---: | ---: | ---: | ---: |
| Производительность, баллы из 100 | 74 | 76 | 96 | 95 |
| FCP, с | 1,1 | 0,8 | 0,3 | 0,2 |
| LCP, с | 7,8 | 8,5 | 1,4 | 1,5 |
| Speed Index, с | 1,4 | 1,2 | 0,3 | 0,4 |
| TBT, мс | 130 | 0 | 40 | 0 |
| CLS | 0,005 | 0 | 0,006 | 0 |

На телефоне AMP набрала на 2 балла больше, а на компьютере на 1 балл меньше. Первый контент в AMP появился быстрее в обоих режимах. Самый крупный элемент отрисовался позже, особенно на телефоне, где LCP вырос с 7,8 до 8,5 с.

[original-mobile]: https://pagespeed.web.dev/analysis/https-sf542-github-io-full-stack_11/88jz17o0cd?form_factor=mobile
[amp-mobile]: https://pagespeed.web.dev/analysis/https-sf542-github-io-full-stack_11-amp-html/q14bzz3unw?form_factor=mobile
[original-desktop]: https://pagespeed.web.dev/analysis/https-sf542-github-io-full-stack_11/88jz17o0cd?form_factor=desktop
[amp-desktop]: https://pagespeed.web.dev/analysis/https-sf542-github-io-full-stack_11-amp-html/q14bzz3unw?form_factor=desktop
