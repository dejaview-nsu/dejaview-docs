# dejaview-docs

Договорённости проекта: архитектура, контракты API, процесс работы, соглашения.

## Содержание

- [architecture.md](architecture.md): компоненты, хранилища, модели, поток индексации
- [process.md](process.md): кто заводит задачи, статусы, жизненный цикл, роли
- [conventions.md](conventions.md): ветки, коммиты, code style, Definition of Done
- [api/openapi.yaml](api/openapi.yaml): контракт REST API
- [contracts/backend-ml.md](contracts/backend-ml.md): контракт backend и ML-сервиса, коллекции Qdrant

## Ссылки

- Задачи и требования: https://ai.nsu.ru/projects/dejaview
- Архитектура, контракты, соглашения: https://github.com/dejaview-nsu/dejaview-docs
- Организация: https://github.com/dejaview-nsu

## Как работаем

- Ветка от `main`: `feat/<номер задачи>-<кратко>`, нейминг в `conventions.md`
- Изменения через Pull Request с ревью, прямой push в `main` закрыт
- Ревьюер назначается автоматически по CODEOWNERS
- Время трекается в Redmine, в задачу, а не в требование
