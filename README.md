# RIFT SYSTEM — ресурспак

Ресурспак для сервера RIFT SYSTEM (Minecraft/Leaf 26.2, `pack_format 88`).

## Скачать

- Прямая ссылка: https://raw.githubusercontent.com/solo0Pb/RiftSystem-resourcepack/main/RiftSystem-resourcepack.zip
- Размер: 369 581 байт
- SHA-1: `dfedd81ae2233acae7da6c3e799d189bfa7d80cc`
- SHA-256: `cea008ed5da31649b029e7c571b6fbcc2ed28451a8186f9660bf280534f5a523`

## Подключение на сервере

В `server.properties`:

```properties
resource-pack=https\://raw.githubusercontent.com/solo0Pb/RiftSystem-resourcepack/main/RiftSystem-resourcepack.zip
resource-pack-sha1=dfedd81ae2233acae7da6c3e799d189bfa7d80cc
require-resource-pack=false
```

`require-resource-pack=false` оставляет игрокам выбор: без пака логика работает, но разломы невидимы.

## Установка в клиент вручную

1. Скачайте ZIP по ссылке выше.
2. Положите в `.minecraft/resourcepacks/`.
3. Включите пак в «Настройки → Наборы ресурсов» и поднимите выше ванильного.

## Содержимое

- `assets/minecraft/models/item/paper.json` — модели разломов (`custom_model_data` 91001–91003)
- текстуры разломов 64×1024 и кадры анимации 64×128
- `pack.mcmeta` с `pack_format 88` и описанием
