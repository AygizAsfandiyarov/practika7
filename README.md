# Отчет по практической работе №7

## Цель работы

Изучение дополнительных возможностей Docker для управления жизненным циклом контейнеров, мониторинга их состояния и оптимизации использования системных ресурсов. Данная практика направлена на глубокое понимание операционных аспектов контейнеризации, что критически важно для построения надежных и масштабируемых приложений в production-среде.

## Подготовка окружения:
Создали директорию
Копировали Dockerfile и entrypoint.sh в директорию
Собрали образ
<img width="974" height="581" alt="image" src="https://github.com/user-attachments/assets/04286809-5211-47c2-af6b-9634a88b0ac9" />

## Задание 1: Вывод логов в файл

<img width="974" height="740" alt="image" src="https://github.com/user-attachments/assets/decce683-3cce-40f9-96e6-ef92031fb8b2" />

## Задание 2: Проверка docker-stats

<img width="974" height="135" alt="image" src="https://github.com/user-attachments/assets/de191ba5-6dd5-49c0-abcc-ecfb350b1303" />

Очистили контейнер
<img width="974" height="116" alt="image" src="https://github.com/user-attachments/assets/94eba6ea-f9ca-40d8-be17-eb0e718f46e8" />

## Задание 3: Ограничение ресурсов
Запуск контейнера с ограничением и проверка статистики
<img width="974" height="245" alt="image" src="https://github.com/user-attachments/assets/f3720d8d-21f1-4a49-b929-1a4b165b8afc" />
Обновление лимитов и очистка
<img width="974" height="192" alt="image" src="https://github.com/user-attachments/assets/ad0d9923-3c48-4849-8f56-eff83e380401" />

## Задание 4: Экспорт в tar

<img width="974" height="720" alt="image" src="https://github.com/user-attachments/assets/106d98a0-c44d-4c49-8d89-dfce9cb2f695" />

## Задание 5: Импорт из tar
Загрузили образ, проверили его наличие. Запустили контейнер из загруженного образа и проверка логов

<img width="974" height="616" alt="image" src="https://github.com/user-attachments/assets/1717112b-857b-415b-b4fd-9e38a7dcd888" />

Очистка
<img width="940" height="214" alt="image" src="https://github.com/user-attachments/assets/3fb03f2b-157f-4bb4-8863-ab1860164109" />




