# ArtVsMark.github.io

Корень `https://artvsmark.github.io/`: страница-указатель на проекты и место,
где поисковые консоли подтверждают права на весь хост. Проекты публикуются
своими репозиториями под своими путями — глоссарий живёт в
[Glossary-Python](https://github.com/ArtVsMark/Glossary-Python) и открывается по
`/Glossary-Python/`.

Почему корень отдельным репозиторием: Яндекс.Вебмастер подтверждает права на
хост целиком и ищет тег на `https://artvsmark.github.io/`, а не в папке проекта.
Тег `yandex-verification` лежит в `index.html`; публикует `.github/workflows/pages.yml`.
