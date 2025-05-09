# PornHub Video Downloader

Современное настольное приложение, созданное на Python с использованием Tkinter, для загрузки видео с Pornhub по URL в максимальном доступном качестве. Приложение имеет стильный тёмный дизайн с оранжевыми акцентами в стиле Pornhub, интеграцию с FFmpeg для обработки видео и удобный интерфейс для комфортной загрузки.

## Возможности

- **Загрузка с Pornhub**: Скачивает видео с Pornhub по предоставленному URL в лучшем доступном качестве, объединяя видео и аудио в формат MP4 с помощью FFmpeg.
- **Автоматическая установка FFmpeg**: Автоматически загружает и настраивает FFmpeg, если он отсутствует, обеспечивая бесперебойную обработку видео.
- **Выбор папки сохранения**: Позволяет пользователю выбрать папку для сохранения загруженных видео.
- **Интеграция с буфером обмена**: Лёгкая вставка URL видео из буфера обмена одним кликом.
- **Современный интерфейс**: Стильный тёмный дизайн с яркими оранжевыми акцентами, вдохновлённый Pornhub.
- **Обработка ошибок**: Чёткие сообщения об ошибках при неверных URL, отсутствии пути сохранения или проблемах с загрузкой.

## Установка

1. **Клонируйте репозиторий**:
   ```bash
   git clone https://github.com/apyxy3/PH-downloader.git
   cd PH-downloader
   ```

2. **Установите зависимости**:
   Убедитесь, что у вас установлен Python 3.6+, затем установите необходимые пакеты:
   ```bash
   pip install -r requirements.txt
   ```

3. **Запустите приложение**:
   ```bash
   python PH.py
   ```

## Требования

- Python 3.6 или выше
- Необходимые Python-пакеты (указаны в `requirements.txt`):
  - `tkinter` (обычно включён в Python)
  - `yt-dlp`
  - `requests`
- Подключение к интернету для загрузки видео и FFmpeg (при первом запуске)

## Использование

1. Запустите приложение, выполнив `PH.py`.
2. Вставьте URL видео с Pornhub в поле ввода с помощью кнопки «Вставить» или введите его вручную.
3. Нажмите кнопку «Скачать видео» и выберите папку для сохранения.
4. Видео будет загружено в максимальном качестве и сохранено в формате MP4 в выбранной папке.

## Примечания

- **FFmpeg**: Приложение автоматически загружает FFmpeg в `C:\ProgramData\PHdownload` на Windows, если он отсутствует. Убедитесь, что у вас есть права на запись в эту папку.
- **Ограничение по платформе**: Приложение предназначено исключительно для загрузки видео с Pornhub. Для других платформ потребуется модификация кода.
- **Только Windows**: Текущая настройка FFmpeg предназначена для Windows. Для других операционных систем потребуется изменить логику установки FFmpeg или вручную предоставить FFmpeg.
- **Юридические аспекты**: Убедитесь, что использование приложения соответствует законодательству вашей страны и правилам Pornhub.

## Лицензия

[MIT License](LICENSE)
