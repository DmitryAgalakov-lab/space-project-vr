#Space Project VR

Учебный VR-проект для Pico 4 и ПК.

## Структура репозитория

-**PC-Version/** - версия проекта для запуска на компьютере (Windows).
-**Android_Version/** - версия проекта для установки на шлем Pico 4 (APK).

## Технологии
- Unity 2022.3 LTS
- Pico SDK
- XR Interaction Toolkit
- C#

## Как запустить версию для ПК
1. Откройте папку PC_Version в Unity 2022.3 LTS
2. Установите Pico SDK.
3. В XR Plug-in Management на вкладке PC включите OpenXR.
4. Соберите проект под Windows (Build - PC, Mac & Linux Standalone).
5. Запустите .exe на компьютере с подключённым шлемом.

## Как запустить версию для шлема
1. Откройте папку PC_Version в Unity 2022.3 LTS.
2. Установите Pico SDK.
3. Смените платформу на Android.
4. В XR Plug-in Managment на вкладке Android включите PICO XR.
5. В Player Settings установите:
   - Minimum API Level = Android 10.0
   - Scripting Backend = IL2CPP
   - Target Architectures = только ARM64
6. Соберите APK: (File - Build Settings - Build).
7. Установите APK на Pico 4.

## Готовые сборки
В репозитории также лежат готовые файлы:
- `PC_Version/SpaceProjectVR.exe`- для запуска на ПК
- `Android_Version/SpaceProjectVR.apk` - для установки на шлем


## Автор
[Дмитрий Агалаков], 10 класс.