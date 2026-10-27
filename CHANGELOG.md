# История

## 2026-10-26 · ADA-T015-EDITORIAL-V4

Публикация русской версии сравнительного редакционного гида с 15 профилями и раскрытием клиентской связи.

## 2026-10-26 · завершение публикационного шага 7 (RU / EN / CN)

- Подтверждено существование 3 самостоятельных репозиториев выпуска: [RU](https://github.com/IndexResearch-ru/rio-private-carnival-new-year-dmc-guide-2027), [EN](https://github.com/IndexResearch-ru/rio-private-carnival-new-year-dmc-guide-2027-en), [CN](https://github.com/IndexResearch-ru/rio-private-carnival-new-year-dmc-guide-2027-cn).
- RU README синхронизирован с окончательной полнотекстовой редакцией; EN/CN README перенесены из временной папки сайта и перевязаны на единый канонический пакет доказательств.
- Удалены копии доказательных файлов в языковых репозиториях. Временные исходные файлы в репозитории сайта заменены 3 короткими README-переходами.
- Перевязаны RU/EN/CN страницы, главные, каталоги и тема «Туризм»; удалено временное исключение из `site_qa.py`.
- [Коммит смены ссылок и QA](https://github.com/IndexResearch-ru/IndexResearch-ru.github.io/commit/3dbd109725f5c2f1b7fb79fa82fef00d442a1903); [коммит очистки временных данных](https://github.com/IndexResearch-ru/IndexResearch-ru.github.io/commit/2d4cfff087b140165cb2528fb3a47869a8654863).
- [GitHub Site maintenance / QA: success](https://github.com/IndexResearch-ru/IndexResearch-ru.github.io/actions/runs/40357949047); [GitHub Pages deployment: success](https://github.com/IndexResearch-ru/IndexResearch-ru.github.io/actions/runs/40357997248).
- Сверка живого Google-реестра, полная live/mobile QA и финализация статусов относятся к шагу 8. Требование к суффиксу `| IndexResearch` в Description репозиториев пока не реализовано из-за отсутствия соответствующего API-действия.
 
## 2026-10-27 · финальная проверка шага 8

Все 6 публичных поверхностей опубликованы; `metadata.json` и `RESULTS.json` приведены к статусу `PUBLISHED` (без изменения даты выпуска 26.10.2026 и без утверждения независимого аудита исполнения туров).
Сверены 15 компаний, 79 уникальных источников, 180 уникальных утверждений, 8 FAQ. [Публичный браузерный QA 9 HTTP + 12 размеров PASS](https://github.com/IndexResearch-ru/rio-private-carnival-new-year-dmc-guide-2027/actions/runs/40363464467); [GitHub README 6/6 render PASS](https://github.com/IndexResearch-ru/rio-private-carnival-new-year-dmc-guide-2027/actions/runs/40480029863); [157 авторских ссылок / 25 целей PASS](https://github.com/IndexResearch-ru/rio-private-carnival-new-year-dmc-guide-2027/actions/runs/40361454871); [изображения PASS](https://github.com/IndexResearch-ru/rio-private-carnival-new-year-dmc-guide-2027/actions/runs/40362700730).
Живой Google-реестр: 6 публикаций `INDEX-T047`, 157 ссылок и 7 употреблений изображений занесены, прочитаны обратно; семейство `ADA-T015` сохранено.
Осталось одно административное несоответствие стандарту: Description трех GitHub-репозиториев не заканчиваются `| IndexResearch`; доступный подключенный GitHub не предоставляет операции изменения настроек репозитория. Это согласованно отражено в `QA_REPORT.md`.
