# Retropie

These are the configs for my personal retropie

## Backup and Recovery

To backup files:

```sh
rsync -av --progress pi@retropie:/opt/retropie/configs/ ./configs/
```

To recover files:

```sh
rsync -av --progress ./configs/ pi@retropie:/opt/retropie/configs/
```

