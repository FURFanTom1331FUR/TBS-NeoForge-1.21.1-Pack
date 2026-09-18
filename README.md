# NeoForge 1.21.1 — модпак

Сборка под **Minecraft 1.21.1 + NeoForge**: атмосферный хоррор **Ambient Dread** и отдельный мод **Hollow Sky**.

## NeoForge (нужная версия)

Ставь **NeoForge 21.1.250** (или новее 21.1.x, не ниже 21.1.250):

- Установщик: https://maven.neoforged.net/releases/net/neoforged/neoforge/21.1.250/neoforge-21.1.250-installer.jar
- Сайт: https://neoforged.net/
- В лаунчере: `neoforge-21.1.250`

```bat
java -jar neoforge-21.1.250-installer.jar --installClient %APPDATA%\.minecraft
```

## Моды в этом репозитории

| Мод | Файл |
|-----|------|
| **Ambient Dread 1.4.3** | [`mods/ambientdread-1.4.3.jar`](mods/ambientdread-1.4.3.jar) |
| **Hollow Sky 1.2.0** | [`mods/hollowsky-1.2.0.jar`](mods/hollowsky-1.2.0.jar) |

Если ставил старую версию — удали старый jar, две версии одного мода вместе не запустятся.

## Опционально: The Broken Script

Если нужен **The Broken Script 2.0.4-hotfix** (~255 МБ, в git не кладём):

- Modrinth: https://modrinth.com/mod/the-broken-script/version/2.0.4-hotfix
- CDN: https://cdn.modrinth.com/data/TocuaDpt/versions/pRPkmb7S/thebrokenscript-neoforge-2.0.4-hotfix%2Bmc1.21.1-build.3291.jar
- Официальные загрузки: https://tbssite.stardustmodding.org/downloads/

## Как поставить

1. Установи NeoForge **21.1.250**.
2. Скачай оба jar из [`mods/`](mods/).
3. (По желанию) скачай TBS с Modrinth.
4. Jar → `%AppData%\.minecraft\mods`.
5. Запуск: профиль **neoforge-21.1.250**.

## Ссылки

- Репозиторий: https://github.com/FURFanTom1331FUR/TBS-NeoForge-1.21.1-Pack
- NeoForge 21.1.250: https://maven.neoforged.net/releases/net/neoforged/neoforge/21.1.250/neoforge-21.1.250-installer.jar
- TBS: https://modrinth.com/mod/the-broken-script
