# DS Проект-2: Анализ рынка труда и сферы Data Science на основе данных HeadHunter

Этот проект предоставляет детальный анализ рынка труда с особым фокусом на сферу Data Science, используя данные с HeadHunter. Проект охватывает широкий спектр: почти 50 000 уникальных вакансий от более чем 23 000 работодателей.

## Содержание

- [Особенности](#особенности)
- [Общий рынок труда](#общий-рынок-труда)
- [Сфера Data Science](#сфера-data-science)
- [Заключение](#заключение)
- [Установка](#установка)
- [Использование](#использование)

## Особенности

- **Исследование** почти 50 000 уникальных вакансий
- **Глубокий анализ** рынка труда в сфере Data Science
- **Географические и зарплатные взгляды**
- **SQL запросы** для эффективного извлечения данных
- **Дружелюбный для новичков** код

## Общий рынок труда

- **49 000 Уникальных Вакансий**
- **23 000 Уникальных Работодателей**
- **Географическое разнообразие**: 1 362 уникальных района
- **Разнообразие отраслей**: 294 уникальные отрасли

## Сфера Data Science

- **1 771 Вакансий** с заголовками, включающими 'data' или 'данные'
- **51 Вакансия для начинающих** без опыта работы
- **201 Вакансий** с ключевыми навыками SQL или Postgres
- **351 Вакансий**, упоминающих Python как ключевой навык

## Заключение

- **Динамичный рынок**: Фокус на крупных городах, таких как Москва и Санкт-Петербург
- **Зарплатные исследования**: Диапазон от 71K до 110K
- **Зарплата в зависимости от навыков в Data Science**: Около 243K RUB для 3-6 лет опыта

## Установка

### Предварительные требования

- Jupyter Notebook

### Шаги по установке

1. **Клонировать репозиторий**

    ```bash
    git clone <https://github.com/TimurShamuradov/DS-Project-2.git>
    cd DS-Project_2
    ```
    
2. **Создать файл конфигурации**

    Создайте файл `config.txt` в папке проекта с вашими учетными данными для базы данных.

    ```
    DBNAME = ваше_имя_базы_данных
    USER = ваше_имя_пользователя
    PASSWORD = ваш_пароль
    HOST = ваш_хост
    PORT = ваш_порт
    ```
    
    ⚠️ **Важно**: Никогда не делитесь файлом `config.txt`.
    
3. **Установить необходимые библиотеки**

    ```bash
    pip install psycopg2-binary
    pip install sqlalchemy
    ```

## Использование

Откройте `DS_Project_2.ipynb` через Jupyter Notebook и выполните ячейки для анализа.
