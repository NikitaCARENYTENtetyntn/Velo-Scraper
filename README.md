![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge) 
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) 
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-4.9.1-orange?style=for-the-badge&logo=html5&logoColor=white) 
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

Мой проект:
🚲 Velo-Scraper: Сбор данных с каталога велосипедов

Проблема, для чего: 
Скрипт создан для автоматизированного сбора актуальных данных о товарах
(**название, цена, прямая ссылка**) с многостраничного онлайн-каталога велосипедов (пример сайта: `www.desporte.ru/catalog/bikes/`).

Используемые технологии:
- **Python 3.x**
- **Requests** (Сетевые запросы)
- **BeautifulSoup** (Парсинг HTML-структуры)
- **Pandas** (Экспорт данных)

Ключевые функции:
1.  **Обработка пагинации:** Скрипт автоматически проходит все страницы каталога, последовательно переходя по параметрам URL (например, `?PAGEN_1=N`).
2.  **Извлечение ключевых данных:** Собирает **Название товара**, его **Цену** и **URL** для каждой позиции в каталоге.
3.  **Чистый экспорт:** Данные экспортируются в структурированный `DataFrame` и сохраняются в файл `.xlsx` для удобной работы.

Результат:

<img width="1657" height="769" alt="image" src="https://github.com/user-attachments/assets/23ddf802-c831-4df8-b471-fae80ebaf615" />
<img width="1732" height="770" alt="image" src="https://github.com/user-attachments/assets/00cccf62-1ba7-4cb1-9512-59c64af4fdf4" />

Инструкция по запуску:
1.  **Клонируйте репозиторий:**
    ```bash
    git clone https://github.com/NikitaCARENYTENtetyntn/Velo-Scraper.git
    ```
2.  **Установите все зависимости:**
    ```bash
    pip install -r requirements.txt
    ```
3.  **Запустите скрипт:**
    ```bash
    python parser.py 
    ```

![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge) 
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) 
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-4.9.1-orange?style=for-the-badge&logo=html5&logoColor=white) 
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
