# P3D Debinaizer

Разбинариватель **Arma 3**: ODOL → MLOD + `model.cfg` (ODOL v75+).

## Скачать

1. Откройте **[Releases](https://github.com/AshcookieKing/P3d-Debinaizer/releases)** (рекомендуется)  
   **или** скачайте файл ниже в корне репозитория:
2. **`P3D_Razbinarizer.exe`** (~155 MB) — один файл, .NET ставить не нужно.

## Запуск

Двойной клик по `P3D_Razbinarizer.exe` → перетащите `.p3d` → **Разбинарить**.

Результат: `имя_mlod.p3d` + `model.cfg`.

## CLI

```bat
P3D_Razbinarizer.exe model.p3d
P3D_Razbinarizer.exe --overwrite model.p3d
```

Параметры: `--no-cfg`, `--cfg-only`, `--overwrite`, `--no-mikero`, `--gui`

## Mikero DeP3d

Если установлен [DePbo Tools](https://mikero.bytex.digital/), включите опцию «Mikero DeP3d» — `model.cfg` будет полнее (sections).

---

© AshcookieKing · MIT
