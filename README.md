<div align="center">

# INDUSTRIAL SMP Launcher

**Установка и умное обновление сборки INDUSTRIAL SMP без ручного копирования файлов.**

[![Latest release](https://img.shields.io/github/v/release/HappYDen-D/SMPLauncher?style=for-the-badge&color=C58A3A&label=РЕЛИЗ)](https://github.com/HappYDen-D/SMPLauncher/releases/latest)
[![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011-1f6feb?style=for-the-badge&logo=windows)](https://github.com/HappYDen-D/SMPLauncher/releases/latest)
[![Minecraft](https://img.shields.io/badge/Minecraft-1.21.1-62b455?style=for-the-badge)](https://industrialsmp.ddns.net/)

[Скачать последнюю версию](https://github.com/HappYDen-D/SMPLauncher/releases/latest) · [Сайт проекта](https://industrialsmp.ddns.net/) · [Discord](https://discord.gg/QyX6z7Kazd)

</div>

---

## Что умеет лаунчер

- Находит установленные Minecraft-лаунчеры и их реальные каталоги сборок.
- Создаёт отдельную установку INDUSTRIAL SMP или обновляет выбранную существующую.
- Загружает только файлы небольшого обновления, когда для текущей версии доступна дельта.
- Проверяет загруженные файлы по SHA-256 и делает резервную копию перед обновлением.
- Сохраняет миры, скриншоты, настройки и другие пользовательские данные.
- Сам сообщает о выходе новой версии программы и умеет обновляться.

## Поддерживаемые лаунчеры

| Лаунчер | Автопоиск | Запуск | Установка/обновление |
|---|:---:|:---:|:---:|
| Prism Launcher / ElyPrism | ✅ | ✅ | ✅ |
| Modrinth App | ✅ | ✅ | ✅ |
| Official Minecraft Launcher | ✅ | при наличии EXE | ✅ |
| TLauncher | ✅ | ✅ | ✅ |
| Legacy Launcher | ✅ | EXE/JAR/BAT | ✅ |
| PineconeMC | ✅ | ✅ | ✅ |
| Lexplosion | ✅ | ✅ | в существующий профиль |

Для Lexplosion сначала создайте профиль **NeoForge 1.21.1** внутри самого Lexplosion, затем выберите этот профиль для обновления в INDUSTRIAL SMP Launcher.

## Быстрый старт

1. Скачайте `INDUSTRIAL_SMP_Launcher.exe` из раздела [Releases](https://github.com/HappYDen-D/SMPLauncher/releases/latest).
2. Запустите файл и выберите найденный Minecraft-лаунчер.
3. Выберите новую установку либо конкретную существующую сборку.
4. Проверьте конечный путь и нажмите **Установить** или **Обновить**.
5. После завершения откройте свой Minecraft-лаунчер и запускайте INDUSTRIAL SMP.

## Об обновлениях

Лаунчер получает актуальный manifest с сервера. Если опубликована цепочка обновления от установленной версии, скачиваются только добавленные и изменённые файлы. При отсутствии подходящей дельты используется полный актуальный архив.

> Windows SmartScreen или браузер могут предупреждать о новом неподписанном EXE. Всегда скачивайте лаунчер только с этой страницы Releases или официального сайта проекта.

## Текущая версия

**Launcher 0.5.4** — поддержка Lexplosion, понятная админ-панель, скрытые служебные окна и подготовка дельта-обновлений.

---

<div align="center">
INDUSTRIAL SMP · Minecraft 1.21.1 · NeoForge
</div>
