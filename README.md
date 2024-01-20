# Курс "big-data" (группа 2024-01)

## Программа курса

- Занятие 0 (1ч) Вводное:
  - Подготовка рабочего места (python, pip, jupyter notebooks, pycharm)
- Занятие 1 (3ч) Краткий обзор Python:
  - создание функций;
  - передача аргументов в функцию;
  - параметры по умолчанию;
  - использование comprehensions;
  - встроенные функции map, filter.
  - переопределение методов;
  - передача аргументов в инициализатор;
  - модули и импорты;
  - организация кода в модули.
  - модули os, pathlib, functools, itertools
- Занятие 2: Обработка данных в Pandas

- Занятие 3: модели машинного обучения
  - модели машинного обучения (логистическая регрессия, деревья, случайный лес) в Scikit-learn
  - применение разных алгоритмов рекомендательных систем

- Занятие 4: Data Lake. Hadoop
  - Обзор архитектуры Data Lake
  - Обзор архитектуры Hadoop (практика запуска hadoop в docker)
  - Концепция map-reduce, hadoop streaming
  - Решение задач на графах
  - Рекомендательные системы

- Занятие: форматы файлов
  - фреймворк apache arrow
  - текстовые форматы (практика с csv|tsv)
  - строковое хранение (практика с avro, protobuf)
  - колоночное хранение (практика с parquet, orc)

- Занятие: Распределенные файловые системы
  - hdfs (практика с cli, практика работы из python)
  - s3, minio (практика работы из python с minio и yandex cloud s3)
  - mongo gridfs

- Занятие: NoSQL
  - Решение задач на графах в neo4j
  - Решение задач полнотекстового поиска в elk
  - Кэширование данных в redis/aerospike (практика на python)

- Занятие Аналитические запросы
  - Аналитические запросы (практика с оконными функциями)
  - SQL-like запросы в Hive для решения аналитических задач, 
  - HBase
  - Clickhouse

- Занятие: Обработка данных в Spark:
  - Архитектура Spark
  - RDD API
  - DataSet/DataFrame/Pandas API
  - UDF на python
  - Spark ML (?)
  - Spark Streaming

- Занятие: Шина данных
  - RabbitMQ/Kafka брокеры сообщений
  - ksql, kafka streaming

- Занятие: Инструменты выгрузки данных:
  - Apache NiFi/Stream Sets
  - CDC Debezium

- Занятие: Оркестрация ETL-процесса:
  - Airflow
