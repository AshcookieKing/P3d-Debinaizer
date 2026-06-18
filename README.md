# P3D Debinaizer

Разбинариватель **Arma 3**: ODOL → MLOD + `model.cfg` (ODOL v75+).

## Скачать

### [⬇ P3D_Razbinarizer.exe — Releases v1.0](https://github.com/AshcookieKing/P3d-Debinaizer/releases/latest/download/P3D_Razbinarizer.exe)

**~155 MB** · один файл · .NET ставить не нужно

> Не скачивайте маленький файл из списка файлов репозитория (это служебный LFS-pointer). Берите exe **только** по ссылке выше или во вкладке [Releases](https://github.com/AshcookieKing/P3d-Debinaizer/releases).

## Запуск

1. Скачайте `P3D_Razbinarizer.exe`
2. Двойной клик → перетащите `.p3d` → **Разбинарить**

Результат: `имя_mlod.p3d` + `model.cfg`

## CLI

```bat
P3D_Razbinarizer.exe model.p3d
P3D_Razbinarizer.exe --overwrite model.p3d
```

| Параметр | Описание |
|----------|----------|
| `--no-cfg` | не создавать model.cfg |
| `--cfg-only` | только model.cfg |
| `--overwrite` | перезаписывать файлы |
| `--no-mikero` | без Mikero DeP3d |

## Mikero DeP3d

Если установлен [DePbo Tools](https://mikero.bytex.digital/), включите «Mikero DeP3d» в окне — `model.cfg` будет с sections.

---

© AshcookieKing
