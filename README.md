Spider `divannewpars` собирает следующие данные о каждом источнике освещения на сайте:

- Название источника освещения
- Цена
- URL-ссылка на страницу товара

## Установка

Перед началом работы убедитесь, что у вас установлен Python и пакетный менеджер pip.

1. **Установите Scrapy**, если он еще не установлен:
   ```bash
   pip install scrapy
   ```

2. **Клонируйте репозиторий** (или создайте директорию для вашего проекта):
   ```bash
   git clone <URL вашего репозитория>
   cd divan_ru
   ```

## Использование

Чтобы запустить spider и начать сбор данных, выполните следующую команду в терминале из корневой директории проекта:

```bash
scrapy crawl divannewpars -o results.json
```

Эта команда запустит spider и сохранит собранные данные в файл `results.json` в формате JSON.

## Настройка

- Убедитесь, что все CSS-селекторы в файле `divannewpars.py` актуальны. Возможно, вам потребуется обновить их, если структура сайта изменится.
- Проверьте, что сайт позволяет скрапинг и соблюдайте его `robots.txt` и условия обслуживания.

## Зависимости

- Python 3.6 или выше
- Scrapy

## Лицензия

Этот проект предоставляется под лицензией MIT. Подробнее см. в файле [LICENSE](LICENSE).

 
