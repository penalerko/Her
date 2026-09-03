# Hermes Backup

آخرین بکاپ: `2026-09-03_09-00-52`
حجم: 4645089 bytes

## ساختار
- `hermes-backup/2026-09-03_09-00-52/hermes.tar.gz` - آرشیو کامل (memories, skills, config, cron, state)
- `hermes-backup/2026-09-03_09-00-52/manifest.json` - اطلاعات بکاپ

## بازیابی
```bash
curl -L -o hermes.tar.gz https://raw.githubusercontent.com/penalerko/Her/main/hermes-backup/2026-09-03_09-00-52/hermes.tar.gz
tar xzf hermes.tar.gz -C ~/.hermes --strip-components=1
```

خودکار هر ۹ ساعت - Cron: `0 */9 * * *`
