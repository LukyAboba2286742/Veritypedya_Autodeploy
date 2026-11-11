# Siteflat

![Deploy](https://github.com/hellriliu/siteflat/actions/workflows/deploy.yml/badge.svg)

Автодеплой через GitHub Actions. Перед публикацией проверяется HTML (HTMLHint) и CSS (Stylelint).

## Пайплайн
1. Проверка качества кода (линтеры HTMLHint и Stylelint).
2. Сборка проекта.
3. Публикация на GitHub Pages.

*Если проверки не пройдены, сайт не обновляется.*
