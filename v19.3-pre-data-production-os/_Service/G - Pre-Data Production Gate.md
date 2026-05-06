# G - Pre-Data Production Gate

## Роль файла

Отделяет архитектурную готовность от фактической бизнес-готовности.

## Статусы

| Статус | Значение |
|---|---|
| ARCHITECTURE READY | структура готова |
| DATA READY | данные собраны |
| MODEL READY | расчёты заполнены |
| FIELD TEST READY | можно тестировать спрос |
| LAUNCH READY | можно запускать |
| NO-GO | запуск опасен |

## Жёсткий запрет

Нельзя ставить **LAUNCH READY** без:

- города;
- района;
- карты конкурентов;
- аренды;
- поставщиков;
- оборудования;
- меню;
- техкарт;
- P&L;
- unit economy;
- cash-flow;
- CAC;
- теста спроса;
- sanitary/legal checklist.

## Текущий статус до данных

```text
Architecture Ready: YES
Data Ready: NO
Model Ready: NO
Field Test Ready: NO
Launch Ready: NO
```

## Главный принцип

До данных проект может быть только **Architecture Ready**. После данных — **Decision Ready**. После теста спроса — **Launch Ready**.
