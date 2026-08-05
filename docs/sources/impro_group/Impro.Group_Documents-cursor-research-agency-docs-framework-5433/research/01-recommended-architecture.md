# Рекомендуемая архитектура документации Impro.group

> Статус: proposal — утвердить после ответов основателей  
> Формат: GitHub markdown handbook (single source of truth)

## Дерево репозитория (целевое)

```text
impro.group_documents/
├── README.md
├── CONTRIBUTING.md
├── CODEOWNERS
│
├── 00-start-here/
│   ├── welcome.md
│   ├── how-to-use.md
│   ├── glossary.md
│   └── decision-log.md
│
├── 01-company/
│   ├── mission-vision-values.md
│   ├── positioning.md
│   ├── strategy.md
│   ├── brand-platform.md
│   ├── operating-principles.md
│   ├── annual-goals.md
│   ├── quarterly-rocks.md
│   └── scorecard.md
│
├── 02-org-people/
│   ├── accountability-chart.md
│   ├── org-structure.md
│   ├── roles/
│   ├── hiring/
│   ├── onboarding/
│   ├── performance/
│   ├── compensation/
│   └── culture/
│
├── 03-legal-corporate/
│   ├── entity-structure.md
│   ├── corporate-governance.md
│   ├── contract-playbook.md
│   ├── templates/
│   │   ├── msa-uslugi.md
│   │   ├── sow.md
│   │   ├── nda.md
│   │   ├── akt.md
│   │   ├── change-order.md
│   │   ├── sla.md
│   │   ├── dpa-pdn.md
│   │   ├── contractor.md
│   │   └── ip-assignment.md
│   └── compliance/
│       ├── 152-fz.md
│       ├── privacy-policy.md
│       ├── cookie-policy.md
│       └── security.md
│
├── 04-sales/
│   ├── icp.md
│   ├── service-catalog.md
│   ├── pricing-models.md
│   ├── sales-process.md
│   ├── discovery.md
│   ├── proposal-template.md
│   ├── qualification.md
│   └── crm-rules.md
│
├── 05-delivery/
│   ├── delivery-principles.md
│   ├── engagement-models.md
│   ├── project-lifecycle.md
│   ├── client-onboarding.md
│   ├── kickoff.md
│   ├── status-reporting.md
│   ├── acceptance.md
│   ├── retrospectives.md
│   ├── offboarding.md
│   └── playbooks/
│       ├── consulting-diagnostic.md
│       ├── marketing-strategy.md
│       ├── performance-marketing.md
│       ├── website-build.md
│       ├── design-brand.md
│       ├── integrations-crm.md
│       ├── chatbots.md
│       └── support-retainer.md
│
├── 06-methodologies/
│   ├── agency-os.md
│   ├── discovery-delivery.md
│   ├── research-methods.md
│   ├── design-standards.md
│   ├── engineering-standards.md
│   └── ai-usage-policy.md
│
├── 07-finance-ops/
│   ├── project-profitability.md
│   ├── utilization.md
│   ├── invoicing.md
│   ├── cashflow.md
│   ├── vendor-management.md
│   └── tools-stack.md
│
├── 08-knowledge/
│   ├── case-library/
│   ├── reusable-frameworks/
│   ├── lessons-learned.md
│   └── expert-directory.md
│
├── 09-products-services/
│   ├── service-catalog.md
│   └── productized-offers/
│
├── 10-templates/
│   ├── sop-template.md
│   ├── playbook-template.md
│   ├── role-card-template.md
│   ├── meeting-notes.md
│   └── postmortem.md
│
├── research/                 # Исследования (этот раздел)
└── questions/                # Вопросы основателям
```

## Таксономия типов документов

| Тип | Когда использовать | Пример |
|-----|--------------------|--------|
| **Principle** | Решение при отсутствии правила | «Клиентский результат важнее внутреннего удобства» |
| **Standard** | Жёсткое правило качества | Coding / design / accessibility baseline |
| **SOP** | Повторяемая процедура | Как выставить акт |
| **Playbook** | Ситуация с суждением | Как спасти сорванный дедлайн |
| **Template** | Заготовка артефакта | Бриф, КП, SOW |
| **Checklist** | Контрольная точка | Pre-launch QA |
| **ADR / Decision** | Зафиксированное решение | Почему MSA+SOW |

## Правила ведения

1. Один документ — один owner (`CODEOWNERS`)
2. В шапке: статус, owner, дата обновления, next review
3. Изменения через PR / review
4. Дубли запрещены — только ссылки
5. Клиентские конфиденциальные материалы **не** хранятся в публичных разделах
6. Юридические шаблоны помечать: `DRAFT — согласовать с юристом`

## MVP-порядок наполнения

См. [`00-synthesis.md`](00-synthesis.md) → раздел Priority tiers.

Рекомендуемый порядок создания папок:

1. `00-start-here`, `01-company`, `04-sales`, `03-legal-corporate/templates`
2. `05-delivery` (lifecycle + 3 ключевых playbook)
3. `02-org-people`, `07-finance-ops`
4. Остальное по мере роста

## Модели engagement (зафиксировать в docs)

1. Diagnostic / Audit — фикс, 1–3 недели  
2. Strategy Sprint — фикс, 2–4 недели  
3. Project Build — milestones / fixed fee  
4. Retainer — маркетинг / advisory  
5. Managed Service + SLA — поддержка / IT / analytics
