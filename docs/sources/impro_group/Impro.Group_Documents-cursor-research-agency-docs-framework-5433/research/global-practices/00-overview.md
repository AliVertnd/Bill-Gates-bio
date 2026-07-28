# Мировые практики: Agency OS, professional services, handbook

> Research note · 2026-07-22

## 1. Agency Operating System

Лучшие агентства строят не «папку документов», а операционную систему:

```text
Principles  →  Standards  →  SOPs  →  Playbooks  →  Templates  →  Checklists
```

Референс структуры: [AgencyOps](https://github.com/Jasonbc/AgencyOps)

| Папка | Назначение |
|-------|------------|
| principles/ | Как принимать решения без готового правила |
| standards/ | Качество across projects |
| sops/ | Повторяемые процедуры с owner/trigger/steps |
| playbooks/ | Ситуации с суждением |
| templates/ | Заготовки артефактов |
| checklists/ | Контрольные точки |
| decisions/ | ADR / зафиксированные решения |

## 2. Knowledge architecture для агентств

Типичные 5 слоёв (AgencyPro / KM practice):

1. Client knowledge — брифы, account playbooks  
2. SOPs — onboarding, QA, invoicing  
3. Brand / creative library  
4. Case studies / proof  
5. People & operating knowledge — org, tools, policies  

Правило: **если вопрос задали дважды — пишем документ**.

## 3. Professional services (McKinsey / BCG / Accenture pattern)

Что переносить в boutique-агентство:

- Practice areas (capabilities)
- Engagement models
- Reusable IP / knowledge assets после каждого проекта
- Expert directory
- Case library (sanitized)

Не переносить слепо: тяжёлую partner hierarchy и избыточный bureaucracy overhead.

## 4. EOS для агентств

Полезные элементы даже без полного EOS:

- **Accountability Chart** — seats, не «люди»
- **Rocks** — 3–7 приоритетов на квартал
- **Scorecard** — weekly метрики
- Один owner на каждую метрику/процесс

https://www.eosworldwide.com/accountability-chart

## 5. Shape Up (Basecamp) для delivery

- Fixed time / budget, variable scope
- Pitch до старта: problem, appetite, solution sketch, risks
- Циклы 2–6 недель
- Betting table для выбора проектов

https://basecamp.com/shapeup/

## 6. GitLab Handbook pattern

Идеальный паттерн для Git-репозитория документов:

- Handbook-first
- Single source of truth
- Изменения через MR/PR
- Ссылки вместо копипаста
- Публичное / приватное разделение по чувствительности

https://handbook.gitlab.com/handbook/

## 7. Legal stack (global standard для consulting/IT)

| Документ | Роль |
|----------|------|
| NDA | До disclosure / discovery |
| MSA | Общие условия отношений |
| SOW | Конкретный проект |
| Change Order | Изменение scope/time/budget |
| DPA | Персональные данные |
| SLA | Managed services |
| IP schedule | Что клиенту / что reusable IP |
| Subcontractor agreement | Downstream защита |

Ключ: **MSA + SOW**, а не один «договор на всё» без приложений.

## 8. Multi-entity в мире

Holding / OpCo имеет смысл при:

- разных рисках (software liability vs media buying)
- отдельных инвесторах
- IP/SaaS продуктах
- международных режимах
- M&A

До этого — **единый бренд + practice P&L + shared services**.

Референсы сетей: Publicis, Stagwell, S4 Capital / Monks — как примеры зонтичных моделей, не как цель копирования.

## 9. Что Impro.group стоит взять прямо сейчас

1. Handbook в Git (этот репозиторий)
2. Таксономию AgencyOps
3. Accountability Chart + scorecard
4. MSA + SOW + Change Order
5. Practice-based org без раннего холдинга
6. После каждого проекта: retrospective + reusable asset + margin note
