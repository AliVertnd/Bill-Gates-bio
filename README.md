# ЖК Талай — аналитика IMPRO × Сибирь Девелопмент

## Для встречи с маркетинг-директором

| Документ | Что это | Объём |
|---|---|---|
| **`docs/deliverables/word/19_модель_стратегического_партнёрства_талай.docx`** | Мандат партнёра, экономика, путь к одобрению | внутренний |
| **`docs/deliverables/word/18_прикладная_записка_разбор_талай.docx`** | Краткая записка для разбора: факты + рекомендации | ~10–15 стр. |
| **`docs/deliverables/word/Исследование_рынок_жилья_Горно_Алтайск_кейс_Талай.docx`** | Научное исследование рынка + кейс «Талай» | ~100+ стр. Word |
| **`docs/deliverables/word/ЖК_Талай_полный_отчёт_IMPRO_СД.docx`** | Полный отчёт на стол основателю (19 глав) | **~113 стр.** Word |
| **`docs/deliverables/14_экспертный_бриф_талай_стратегический_партнёр.md`** | Единый бриф: проект + рынок + роль IMPRO | полочки A–K · править по пунктам |
| **`docs/deliverables/08_полный_документ_талай.md`** | Master v2.0 — полный анализ | ~1 000 строк / ~10 тыс. слов |
| **`docs/deliverables/10_презентация_md_8_13.md`** | Выжимка 12 слайдов | обсуждение, не продажа |

Черновики глав отчёта: `docs/deliverables/full_report_parts/`. Сборка Word: `scripts/build_talay_full_docx.py`.

## Как собрано

Параллельные агенты по блокам → верификация → anti-hallucination audit → master → deck.

| Слой | Файл |
|---|---|
| Hard data verification | `docs/working/10_hard_data_verification.md` |
| Gateway thesis | `docs/working/10_gateway_thesis_углубление.md` |
| Спрос / сегменты | `docs/working/10_спрос_сегментация_талай.md` |
| Конкуренты | `docs/working/05_конкуренты_domrf.md` |
| Аренда revised | `docs/working/06_gateway_rental_model.md` |
| Воронка продаж | `docs/deliverables/11_воронка_и_система_продаж_талай.md` |
| Соцсети | `docs/working/09_соцсети_тренды_алтай.md` |
| Партнёры | `docs/working/08_ан_ук_медиа_подрядчики.md` |
| Anti-hallucination | `docs/working/11_anti_hallucination_audit.md` |

## Структура репо

- `docs/sources/` — меморандумы + модель IMPRO (zip)
- `docs/working/` — исследовательские слои
- `docs/deliverables/` — материалы встреч
- `data/` — CSV hard data

**Тон встречи:** обсуждение данных и улучшений. Внутренний офер IMPRO (`deliverables/06`) на эту встречу не выносить.
