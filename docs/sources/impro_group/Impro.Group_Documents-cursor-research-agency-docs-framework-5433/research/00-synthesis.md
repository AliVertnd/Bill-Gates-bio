# Сводка исследования: что нужно Impro.group

> Дата: 2026-07-22  
> Статус: research draft  
> Цель: понять, какие документы, оргструктура и юрлица нужны гибридному агентству маркетинг + IT + консалтинг.

> **Исправление 2026-07-22:** impro.pro / IMpro — **не наш бренд**, а конкурент. Актуальный контекст компании — в `questions/otvety-osnovatelej.md` и `00-nachalo/karta-sistemy.md`.


## 1. Кто мы (по текущему позиционированию)

По публичным материалам [impro.pro](https://impro.pro/):

- digital / internet-маркетинг агентство с 2014
- услуги: сайты, продвижение, дизайн, интеграции, чат-боты, консалтинг, поддержка
- фокус: SMB + федеральные проекты
- формат: агентство полного цикла digital-коммуникаций

Это важно: Impro.group — не «чистый» креатив и не «чистый» IT-интегратор, а **гибрид professional services**. Значит, документация должна покрывать и agency delivery, и consulting engagement, и product/IT delivery.

---

## 2. Ключевые выводы из лучших кейсов

### РФ

| Кейс | Модель | Урок для Impro.group |
|------|--------|----------------------|
| [IT-Agency](https://www.it-agency.ru/academy/it-agency-inside/) | Автономные бизнес-юниты, Совет, P&L, OKR, shared services | Автономия практик работает только с прозрачными финансами и правилами управления |
| [Notamedia](https://nota.media/company/) | Agency + IT-интегратор в одной группе | Маркетинг и IT можно разделять организационно и юридически |
| [AGIMA](https://www.agima.ru/approach/) | Независимые проектные офисы | Портфель клиентов + ответственность PM за маржу и NPS |
| [AIC](https://aic.ru/agency) | Design/CX/консалтинг, сильная культура качества | Нужна quality doctrine и принципы принятия решений |
| [Red Keds](https://redkeds.com/company) | Компактное ядро + сеть креаторов | Contractor-контур должен быть формализован (NDA, IP, QA) |
| [iConText Group](https://icontextgroup.ru/) | Группа специализированных digital-компаний | «Группа» удобна для роста экспертиз под одним брендом |
| [ADVAGA](https://advaga.group/) | Holding: реклама + IT + консалтинг + продукты | Близкий архетип к Impro.group при масштабировании |

### Мир

| Практика | Суть | Урок |
|----------|------|------|
| GitLab Handbook | Markdown handbook как single source of truth | Документы меняются через PR, без «финал_v7.docx» |
| EOS (Traction) | Accountability Chart, Rocks, Scorecard | Один owner на роль/метрику/процесс |
| Basecamp Shape Up | Fixed time / variable scope, betting table | Фиксировать appetite до старта проекта |
| McKinsey / BCG / Accenture | Practice areas + industries + reusable IP | Строить практики и библиотеку методологий |
| AgencyOps / Agency KM | Principles → Standards → SOPs → Playbooks → Templates | Чёткая таксономия документов |
| MSA + SOW | Рамка + проектные приложения | Базовый стандарт professional services |

---

## 3. Что потребуется Impro.group

### 3.1. Организационная модель (рекомендация)

На старте / при команде ~5–30 человек:

```text
Founders / Partners
└── Impro Council (партнёрский / управленческий совет)
    ├── Practice: Strategy & Consulting
    ├── Practice: Marketing & Performance
    ├── Practice: Creative & Brand
    ├── Practice: Product & IT
    ├── Practice: Analytics & Research (по мере роста)
    └── Shared Services
        ├── Sales / Growth
        ├── Delivery Ops / PM
        ├── Finance
        ├── Legal / Compliance
        ├── HR / People
        └── Knowledge Base
```

**Не начинать** с тяжёлой иерархии и не копировать holacracy целиком.  
Лучший баланс: **практики + проектные команды (pods) + shared services**.

### 3.2. Юридическая модель (варианты)

| Вариант | Когда | Плюсы | Минусы |
|---------|-------|-------|--------|
| **A. Одно ООО** | Старт, IT-выручка не доминирует | Проще учёт, один бренд | Сложнее IT-аккредитация, смешанные риски |
| **B. Два ООО** (Agency + Tech) | Планируется Минцифры / серьёзный IT P&L | Чистая IT-выручка, разные шаблоны договоров | Двойная бухгалтерия, договоры между юрлицами |
| **C. Группа / холдинг** | Разные партнёры, продукты, M&A | Масштаб, риск-сепарация | Сложность управления |
| **D. ООО + ИП/самозанятые** | Гибкий production | Масштабирование без ФОТ | Риск переквалификации в трудовые отношения |

**Практическая рекомендация сейчас:**  
управленчески уже делить P&L по практикам; юридически — **одно ООО**, если нет явной цели IT-аккредитации. Если цель есть — проектировать **два ООО** заранее и вести учёт IT-выручки отдельно с первого дня.

> Это не юрзаключение. Финальный выбор — с юристом и бухгалтером.

### 3.3. Пакеты документов (обязательные контуры)

1. **Company / Strategy** — миссия, позиционирование, оргструктура, OKR
2. **Corporate** — устав, корпоративный договор, протоколы, доли
3. **Legal templates** — MSA, SOW, NDA, акт, SLA, change request, IP
4. **HR / People** — ТД, ЛНА, грейды, onboarding/offboarding
5. **Sales** — ICP, бриф, КП, прайс, CRM-правила
6. **Delivery** — lifecycle, kickoff, RACI, playbooks по услугам
7. **Finance** — маржа проекта, utilization, дебиторка, P&L практик
8. **Compliance** — 152-ФЗ, ПДн, cookies, доступы, security
9. **Knowledge** — кейсы, шаблоны, lessons learned, reusable IP

---

## 4. Priority tiers

### Tier 0 — MVP (сделать первым)

Документы, без которых агентство работает «на людях в головах»:

1. Миссия / позиционирование / услуги
2. Accountability chart (кто за что отвечает)
3. Каталог услуг + модели engagement
4. Sales process + шаблон КП
5. Договор услуг (MSA) + SOW + NDA + акт + change request
6. Client onboarding + project lifecycle
7. Status report + acceptance
8. Калькулятор / правила маржи проекта
9. Шаблон SOP / playbook
10. Decision log

### Tier 1 — Scale

- Роли и career ladder
- Hiring / onboarding / offboarding
- Playbooks по каждой услуге
- Contractor agreements + IP assignment
- DPA / SLA
- Finance scorecard
- Case library
- Политика AI / security / ПДн внутри компании

### Tier 2 — Mature

- Practice portals
- Multi-entity governance
- Communities of practice
- Internal audit
- Board reporting
- Methodology certification

---

## 5. Что делать дальше

1. Основатели отвечают на [`../questions/founders-intake.md`](../questions/founders-intake.md)
2. Утверждаем архитектуру [`01-recommended-architecture.md`](01-recommended-architecture.md)
3. Создаём скелет `docs/` и наполняем Tier 0
4. Параллельно собираем факты о текущем состоянии: юрлица, команда, договоры, процессы

---

## 6. Источники (основные)

- IT-Agency inside: https://www.it-agency.ru/academy/it-agency-inside/
- eLama — структура маркетингового агентства: https://elama.ru/blog/struktura-marketingovogo-agentstva/
- Timetta — professional services model: https://timetta.com/ru/blog/professional-services-business
- AgencyOps: https://github.com/Jasonbc/AgencyOps
- GitLab Handbook: https://handbook.gitlab.com/handbook/
- Shape Up: https://basecamp.com/shapeup/
- EOS Accountability Chart: https://www.eosworldwide.com/accountability-chart
- Минцифры / IT-аккредитация (ПП №1729): https://sudact.ru/law/postanovlenie-pravitelstva-rf-ot-30092022-n-1729/
- ФНС о самозанятых и трудовых отношениях: https://www.nalog.gov.ru/
