# O - Launch Readiness Index

## Роль файла

Индекс готовности проекта к запуску. Используется в 39 и 55 перед любым решением о старте.

## Главный принцип

Launch Ready нельзя ставить по ощущению. Только по закрытым блокам, данным и Decision Gate.

## Индекс готовности

| Блок | Вес | Статус |
|---|---:|---|
| Рынок и район | 10 | OPEN |
| Конкуренты | 8 | OPEN |
| Спрос / MVP | 10 | OPEN |
| Меню | 8 | OPEN |
| Техкарты и food cost | 10 | OPEN |
| Помещение | 8 | OPEN |
| Оборудование и CAPEX | 8 | OPEN |
| Кухня и capacity | 8 | OPEN |
| Доставка и SLA | 6 | OPEN |
| Команда и ФОТ | 6 | OPEN |
| CRM / касса / учёт | 6 | OPEN |
| P&L | 8 | OPEN |
| Unit economy | 8 | OPEN |
| Cash-flow | 10 | OPEN |
| Legal / sanitary | 12 | OPEN |
| Retention | 6 | OPEN |
| Риски и stress-test | 8 | OPEN |

## Интерпретация

| Балл | Статус | Решение |
|---:|---|---|
| 0–49 | Not Ready | NO-GO |
| 50–69 | Architecture/Data Partial | HOLD |
| 70–84 | Candidate | FIX |
| 85–94 | Almost Ready | REVIEW |
| 95–100 | Launch Ready | GO при отсутствии блокеров |

## Абсолютные блокеры

Даже при высоком балле запуск запрещён, если не закрыты:

- legal/sanitary;
- P&L;
- unit economy;
- cash-flow;
- food cost;
- kitchen capacity;
- delivery SLA;
- market validation.

## Формат вывода

```text
Launch Readiness Index:
Общий балл:
Статус:
Блокеры:
Что исправить:
Срок:
Владелец:
Decision Gate:
```
