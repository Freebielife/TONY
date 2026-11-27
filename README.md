# Tony from TON Observatory

## О проекте / токене

По официальному сайту, TONY — управляемый сообществом мем-токен в сети TON, связанный с персонажем Tony McDuck и набором стикеров. Сайт прямо указывает, что это не официальный проект TON.

Краткое описание по указанным первичным источникам.

Источники (проверены 2026-11-24):

- <https://tonyfromton.com/>
- <https://tonapi.io/v2/jettons/EQAH8OSNymywSQyPE1t0tULFlxO__yhUmlscpTCfMLf_TONY>

Generated from https://github.com/Freebielife/TON-Observatory-Template.

Run python3 -m scripts.refresh_observatory; python3 build.py; python3 verify.py.
Publish index.html in TON Sites only after independent on-chain verification.
Данные получены из TonAPI и GeckoTerminal. Статусы и полнота разделов указаны в data/snapshot.json и интерфейсе; отсутствие подтверждения не заменяется вымышленными значениями.
Only native TON swap pairs supported. Locks, staking and custom project NFT badges are configured through project.json and verified against TonAPI.
В update.yml подготовлен запуск каждые 30 минут (17-я и 47-я минуты часа). Фактическое выполнение проверяется отдельно после публикации. GitHub Actions может задерживать плановые запуски.

Foundation version: 1.3.0. Holders show 10, expandable to top 20.
`project.json` is the per-project specification. Contract/pool/precision changes require regenerating from the factory; do not reuse another token's snapshot.
Run `python3 build.py` for an atomic bundle and `build/report.json` size report.
No external fonts, scripts or images are needed to render the saved page. Fresh data checks and manual wallet lookups require network access.
Cloudflare dispatch registration and GitHub repository access remain separate deployment steps. No credentials go into HTML.

Изображение баннера и флага: предоставлено пользователем image(20261124-194748).png.

Для Resistance Tools / TON Storage загрузите только index.html. Изображения, стили и скрипты встроены. Обновление данных из GitHub требует сети и опубликованного snapshot.json.
