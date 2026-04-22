# YTUVI — Season 1

Бриф первого сезона ювелирно-геммологического канала **YTUVI**.

➡️ **Сайт:** https://romansergeevcom.github.io/YTUVI-S1/

## Что внутри

- [index.html](index.html) — single-page бриф (public build): 5 тем по камням + flagship-пилот, тезисы из Zoom-встречи 2026-04-21, библиотека референс-видео Натальи с её комментариями и тайм-кодовыми транскриптами.
- [refs/](refs/) — YouTube-транскрипты reference-видео в JSON (исходник для rebuild).

## Season 1 · 6 выпусков

1. **YTUVI-001** — Корунд · Рубин (Бирма, pigeon blood, insider-рынок, Harry Winston)
2. **YTUVI-002** — Корунд · Сапфир и Падпараджа (Кашмир, fancy sapphire, рассвет/закат)
3. **YTUVI-003** — Гранаты: цаворит, демантоид, спессартин (легенда Бриджеса)
4. **YTUVI-004** — Шпинель и Корона Российской империи (историческая подмена, Mahenge)
5. **YTUVI-005** — Изумруд (масло, Colombia vs Zambia, сертификация)
6. **YTUVI-006** — Flagship explainer «How to Identify Gemstones» 1-в-1 на русском (5–8 мин пилот)

## Rebuild

HTML self-contained (всё встроено). Пересборка — через `build_brief.py` в [YTAI-репо](https://github.com/RomanSergeevCom/YTAI):

```bash
python3 ~/YTAI/scripts/999_extra/ytuvi_brief_builder/build_brief.py \
  --refs-dir ~/repos/YTUVI-S1/refs \
  --out ~/repos/YTUVI-S1/index.html
```

## Structure

- ⭐ Flagship: «How to Identify Gemstones» (JTV/Gemstones) — шаблон для RU-адаптации
- 5 камней: концепт + идеи + референсы по теме
- 📚 Общая библиотека: Gem Tools, Gem vs Gem Death Match
- 🎙️ Zoom-встреча 2026-04-21 — транскрипт (обновится после Whisper)
