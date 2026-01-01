شرح مختصر عن تكامل التطبيق مع DummyJSON (API فقط)

- Base URL: `https://dummyjson.com` (`lib/helpera/constants.dart`).
- الموارد: `todos`.

- Endpoints:
  - GET `/todos`
  - POST `/todos/add` (body: `todo`, `completed`, `userId`, `description`)
  - PUT `/todos/{id}` (body: `todo`, `completed`, `description`)
  - DELETE `/todos/{id}`

