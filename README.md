<div align="center">

# INDUSTRIAL SMP Launcher

**Установка, запуск и безопасное обновление сборки INDUSTRIAL SMP без ручного копирования файлов.**

[![Latest release](https://img.shields.io/github/v/release/HappYDen-D/SMPLauncher?style=for-the-badge&color=C58A3A&label=РЕЛИЗ)](https://github.com/HappYDen-D/SMPLauncher/releases/latest)
[![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011-1f6feb?style=for-the-badge&logo=windows)](https://github.com/HappYDen-D/SMPLauncher/releases/latest)
[![Minecraft](https://img.shields.io/badge/Minecraft-1.21.1-62b455?style=for-the-badge)](https://industrialsmp.ddns.net/)

[Скачать EXE](https://github.com/HappYDen-D/SMPLauncher/releases/latest/download/INDUSTRIAL_SMP_Launcher.exe) · [Все релизы](https://github.com/HappYDen-D/SMPLauncher/releases) · [Сайт проекта](https://industrialsmp.ddns.net/) · [Discord](https://discord.gg/QyX6z7Kazd)

</div>

---

## Главное

INDUSTRIAL SMP Launcher может самостоятельно установить Minecraft, NeoForge и актуальную сборку в отдельную папку. Prism Launcher или TLauncher для рекомендуемого режима больше не нужны.

- Вход через Microsoft или запуск по офлайн-нику.
- Установка игры в `%AppData%\INDUSTRIAL SMP\game`.
- Выбор оперативной памяти от 4 до 16 ГБ.
- Проверка и восстановление недостающих файлов.
- Безопасное удаление установленной игры из интерфейса.
- Автоматическая проверка обновлений программы и сборки.
- Подробный прогресс: скорость, передано/всего и оставшееся время.

Адрес сервера: `industrialssmp.ddns.net:25569`.

## Быстрый старт

1. Скачайте [INDUSTRIAL_SMP_Launcher.exe](https://github.com/HappYDen-D/SMPLauncher/releases/latest/download/INDUSTRIAL_SMP_Launcher.exe).
2. Запустите файл. Установка программы не требуется.
3. Войдите через Microsoft либо укажите ник из 3–16 символов.
4. Выберите объём оперативной памяти.
5. Нажмите **Установить и играть**. Лаунчер загрузит необходимые компоненты и подключит сервер.

При следующем запуске достаточно нажать **Играть**. Кнопка **Проверить файлы** восстанавливает недостающие файлы сборки и не удаляет личные дополнительные моды без необходимости.

## Существующие Minecraft-лаунчеры

Дополнительный режим позволяет установить или обновить INDUSTRIAL SMP внутри уже используемого лаунчера.

| Лаунчер | Автопоиск | Запуск | Установка/обновление |
|---|:---:|:---:|:---:|
| Prism Launcher / ElyPrism | ✅ | ✅ | ✅ |
| Modrinth App | ✅ | ✅ | ✅ |
| Official Minecraft Launcher | ✅ | при наличии EXE | ✅ |
| TLauncher | ✅ | ✅ | ✅ |
| Legacy Launcher | ✅ | EXE/JAR/BAT | ✅ |
| PineconeMC | ✅ | ✅ | ✅ |
| Lexplosion | ✅ | ✅ | в существующий профиль |

Для Lexplosion сначала создайте профиль **NeoForge 1.21.1** внутри самого Lexplosion, затем выберите этот профиль в INDUSTRIAL SMP Launcher.

## Как работают обновления

Лаунчер получает размеры и SHA-256 файлов с сервера обновлений. Если для установленной версии доступна цепочка небольших патчей, скачиваются только изменённые файлы. Перед изменением управляемых каталогов создаётся резервная копия, а миры, скриншоты и пользовательские настройки сохраняются.

Обновление самого лаунчера публикуется отдельным EXE. Сначала загружается и проверяется новый файл, после чего текущая программа безопасно заменяется и перезапускается.

## Версия 0.7.24

- Исправлено обновление модов в модернизированном режиме: новые файлы больше не откатываются на старую папку.
- Подготовлена поддержка актуальной клиентской сборки 1.1.19 с Create Ore Excavation и без WebDisplays.
- Номер программы приведён к единой версии 0.7.24 во всех экранах и метаданных.

Полная история изменений находится в [CHANGELOG.md](CHANGELOG.md).

## Проверка и безопасность

- Загружайте EXE только из раздела [Releases](https://github.com/HappYDen-D/SMPLauncher/releases) или с официального сайта.
- Для каждого актуального релиза публикуется файл [`INDUSTRIAL_SMP_Launcher.exe.sha256`](https://github.com/HappYDen-D/SMPLauncher/releases/latest/download/INDUSTRIAL_SMP_Launcher.exe.sha256).
- Пароль административной публикации не сохраняется лаунчером.
- Данные Microsoft-аутентификации хранятся локально в профиле пользователя.

Windows SmartScreen или браузер могут предупреждать о новом неподписанном EXE. Это ожидаемо для файла без сертификата Authenticode; сверяйте источник и SHA-256.

## Если что-то не работает

1. Полностью закройте Minecraft перед проверкой или обновлением файлов.
2. Убедитесь, что антивирус или прокси не блокирует `industrialsmp.ddns.net` и GitHub Releases.
3. Повторите операцию: сетевые загрузки поддерживают повторные попытки, а незавершённые временные файлы не публикуются как готовые.
4. Если ошибка повторяется, приложите её текст и время возникновения в [Discord проекта](https://discord.gg/QyX6z7Kazd).

---

<div align="center">
INDUSTRIAL SMP · Minecraft 1.21.1 · NeoForge · Launcher 0.7.24
</div>
