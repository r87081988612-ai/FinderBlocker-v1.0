# FinderBlocker

FinderBlocker — инструмент для поиска и фиксации зеркал сайтов по ряду признаков.

## 🚀 Использование

1. Скачайте готовый `.exe` из раздела Releases.
2. Запустите его — появится графическое окно.
3. Укажите параметры и нажмите **Start**.

## 🛠️ Сборка вручную

```powershell
pip install -r requirements.txt
pyinstaller --onefile --noconsole --name=finder_blocker_gui finder_blocker_gui.py
```

Готовый файл будет лежать в `dist/finder_blocker_gui.exe`.
