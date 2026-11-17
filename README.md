# Osint-Project

Учебный OSINT-аудит цифрового следа. Прогоняет фото, ник и email через EXIF, Sherlock, Holehe, HIBP и SpiderFoot и собирает отчёт с графом связей.

## Запуск

Linux / macOS:

```bash
unzip osint_project.zip -d osint_project
cd osint_project
bash install.sh
bash start.sh
```

Windows: распаковать архив, запустить `install.bat`, потом `start.bat`.

Можно сразу с параметрами:

```bash
bash start.sh --photo photo.jpg --username ivan_petrov --email ivan@example.com
```

Подробное описание — в `README.md` внутри архива.
