# Домашнее задание к занятию 4 «Работа с roles»

## Ссылки на репозитории:

1. **Репозиторий роли Vector:** [vector-role](https://github.com/S1ugger96/vector-role) (тег `1.0.0`)
2. **Репозиторий роли LightHouse:** [lighthouse-role](https://github.com/S1ugger96/lighthouse-role) (тег `1.0.0`)
3. **Репозиторий с Playbook:** [ansible-hw-roles](https://github.com/S1ugger96/ansible-hw-roles)

## Описание

- Роль ClickHouse подключается внешней зависимостью через `requirements.yml`.
- Роли `vector-role` и `lighthouse-role` вынесены в отдельные независимые репозитории с версионированием через Git-теги.
- Главный плейбук `site.yml` объединяет запуск всех трёх ролей.
