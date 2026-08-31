# Hermes Backup

آخرین بکاپ: `2026-08-31_09-00-30`
حجم: 4643605 bytes

## ساختار
- `hermes-backup/2026-08-31_09-00-30/hermes.tar.gz` - آرشیو کامل (memories, skills, config, cron, state)
- `hermes-backup/2026-08-31_09-00-30/manifest.json` - اطلاعات بکاپ

## بازیابی
```bash
curl -L -o hermes.tar.gz https://raw.githubusercontent.com/penalerko/Her/main/hermes-backup/2026-08-31_09-00-30/hermes.tar.gz
tar xzf hermes.tar.gz -C ~/.hermes --strip-components=1
```

خودکار هر ۹ ساعت - Cron: `0 */9 * * *`
