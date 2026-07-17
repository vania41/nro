# nro

Минимальная раздача **marmelad.nro** для копирования через DBI.

## DBI (`sdmc:/switch/DBI/dbi.config`)

```ini
[Network sources]
Marmelad=URLList|https://vania41.github.io/nro/dbi.txt
```

Файл списка (`dbi.txt`) — формат URLList: `имя|url` по строке.

Прямая ссылка на релиз:
`https://github.com/vania41/nro/releases/latest/download/marmelad.nro`

## Обход без DBI

С ПК/Mac:

```bash
curl -L -o marmelad.nro https://github.com/vania41/nro/releases/latest/download/marmelad.nro
```

Положить на SD: `switch/marmelad/marmelad.nro`
