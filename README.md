# YTUVI — Season 1

Бриф первого сезона ювелирно-геммологического канала **YTUVI**.

➡️ **Сайт:** https://romansergeevcom.github.io/YTUVI-S1/

## Что внутри

- [index.html](index.html) — single-page бриф: 5 тем по камням (сапфир/рубин, падпараджа, гранаты, шпинель, изумруд), flagship-референс «How to Identify Gemstones» (повторить 1-в-1 на RU), библиотека референс-видео Натальи с её комментариями и тайм-кодовыми транскриптами, транскрипт Zoom-встречи 2026-04-21.
- [refs/](refs/) — YouTube-транскрипты reference-видео в JSON (исходник для rebuild).

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
