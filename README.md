# Bitrix REST task diagnostic

Минимальная диагностическая страница для проверки REST scope `task` на тестовом Bitrix24.

Проверяет:
- `scope`;
- `methods`;
- `task.item.getmanifest`;
- `task.logitem.list` для одной тестовой задачи.

## Privacy

Страница не отправляет ответы REST на GitHub или другие внешние сервисы.  
Для истории задачи UI показывает только список типов событий и события `STAGE_ID`.

Используйте только тестовые задачи без персональных данных.

## Bitrix local app URLs

После публикации GitHub Pages:

- Handler: `https://burangulovruslan.github.io/bitrix-rest-test/`
- Initial installation: `https://burangulovruslan.github.io/bitrix-rest-test/install.html`

В правах локального приложения выбрать `Задачи (task)`.
