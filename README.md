# Architecture Alexandrite

![Project Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue.svg)
![Documentation](https://img.shields.io/badge/Documentation-Complete-success)

## 📋 Описание проекта

Проект представляет собой комплексный архитектурный анализ и решения по улучшению IT-системы компании «Александрит» - производителя ювелирных украшений на заказ. В рамках 6-го спринта курса Software Architecture были разработаны решения по мониторингу, трейсингу, логированию и кешированию для системы, включающей онлайн-магазин, CRM и MES.

## 🏗️ Архитектура системы

### Технологический стек

**Frontend:**
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat&logo=vue.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat&logo=three.js&logoColor=white)

**Backend:**
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=spring-boot&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=c-sharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-5C2D91?style=flat&logo=.net&logoColor=white)

**Базы данных и хранилища:**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat&logo=elasticsearch&logoColor=white)
![Amazon S3](https://img.shields.io/badge/Amazon_S3-FF9900?style=flat&logo=amazon-s3&logoColor=white)

**Инфраструктура и мониторинг:**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat&logo=rabbitmq&logoColor=white)
![Jaeger](https://img.shields.io/badge/Jaeger-0082C6?style=flat&logo=jaeger&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat&logo=apache-kafka&logoColor=white)
![Apache Flink](https://img.shields.io/badge/Apache_Flink-E6526F?style=flat&logo=apache-flink&logoColor=white)
![InfluxDB](https://img.shields.io/badge/InfluxDB-22ADF6?style=flat&logo=influxdb&logoColor=white)

**Визуализация и анализ:**
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![Kibana](https://img.shields.io/badge/Kibana-005571?style=flat&logo=kibana&logoColor=white)
![OpenSearch](https://img.shields.io/badge/OpenSearch-005EB8?style=flat&logo=opensearch&logoColor=white)

## 📁 Структура проекта

```
architecture--alexandrite/
├── Task1/                          # Анализ и планирование
│   └── Планирование_анализ_идентификация_проблем_и_поиск_решений.md
├── Task2/                          # Мониторинг
│   └── Выбор и настройка мониторинга в системе.md
├── Task3/                          # Трейсинг
│   ├── Архитектурное решение по трейсингу.md
│   └── jewerly_c4_model_update.drawio
├── Task4/                          # Логирование
│   └── Архитектурное решение по логированию.md
├── Task5/                          # Кеширование
│   ├── Архитектурное решение по кешированию.md
│   └── caching_sequence_diagrams.drawio
├── docs/                           # Дополнительная документация
│   ├── jewerly_c4_model.drawio
│   └── req.md
└── README.md
```

## 🎯 Основные задачи и решения

### Task 1: Анализ архитектуры и планирование
- 🔍 Анализ текущей архитектуры системы
- 🚨 Идентификация проблемных мест
- 📈 Разработка инициатив по улучшению
- 🗓️ Планирование целевой архитектуры

### Task 2: Система мониторинга
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)

- 📊 Выбор метрик для мониторинга (RED/USE подходы)
- ⚡ Настройка мониторинга производительности
- 🔔 Алертинг и уведомления
- 📈 Dashboard'ы для операционной команды

### Task 3: Распределенный трейсинг
![Jaeger](https://img.shields.io/badge/Jaeger-0082C6?style=flat&logo=jaeger&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat&logo=elasticsearch&logoColor=white)

- 🔗 Сквозная трассировка заказов
- 🤖 Автоматический мониторинг и алертинг
- 🧠 ML-анализ аномалий
- 🔄 Auto-healing для зависших заказов

### Task 4: Централизованное логирование
![OpenSearch](https://img.shields.io/badge/OpenSearch-005EB8?style=flat&logo=opensearch&logoColor=white)
![Logstash](https://img.shields.io/badge/Logstash-005571?style=flat&logo=logstash&logoColor=white)

- 📝 Структурированное логирование
- 🔍 Быстрый поиск и анализ логов
- 🛡️ Политики безопасности и хранения
- 📊 Превращение в систему анализа

### Task 5: Кеширование
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)

- ⚡ Ускорение MES интерфейса операторов
- 📋 Кеширование списков заказов
- 🔄 Стратегии инвалидации кеша
- 📈 Повышение производительности в 8-10 раз

## 📊 Ключевые метрики улучшений

### Технические показатели
- **MTTR**: Сокращение с 4,8 часов до 15, 30 минут (в 10, 15 раз)
- **Page Load Time**: Улучшение с 5,8 секунд до 0.5, 1 секунды (в 8,10 раз)
- **System Observability**: Рост с 20% до 90% (в 4.5 раза)
- **Database Load**: Снижение нагрузки на 70, 80%

### Бизнес-показатели
- **Order Loss Rate**: Снижение с 5% до 0.5% (в 10 раз)
- **Operator Productivity**: Рост на 80%
- **Customer Satisfaction**: Рост на 30, 40%
- **Support Team Productivity**: Рост на 50%

## 🏛️ Архитектурные принципы

- **🔍 Observability First**: Полная видимость всех процессов
- **🔄 Event-Driven Architecture**: Реактивная архитектура с RabbitMQ
- **📈 Horizontal Scalability**: Возможность масштабирования компонентов
- **🛡️ Security by Design**: Безопасность на всех уровнях
- **🚀 Performance Optimization**: Оптимизация производительности как приоритет

## 📋 C4 диаграммы

Проект включает детализированные C4 диаграммы:
- 🔍 **С трейсингом**: `Task3/jewerly_c4_model_update.drawio`
- ⚡ **Диаграммы кеширования(sequence diagrams)**: `Task5/caching_sequence_diagrams.drawio`

## 🚀 Результаты проекта

### Решенные проблемы
- ❌ Потерянные заказы → ✅ Полная трассируемость
- ❌ Медленный MES интерфейс → ✅ Мгновенная загрузка
- ❌ Долгая диагностика → ✅ Автоматическое выявление проблем
- ❌ Неудовлетворенность B2B клиентов → ✅ Быстрая обработка заказов

### Технологическая модернизация
- 🔧 Внедрение современного observability стека
- 📊 Автоматизация мониторинга и алертинга  
- 🤖 ML-подходы для предиктивной аналитики
- ⚡ Кардинальное улучшение производительности

## 👥 Команда проекта

**Роль**: Software Architect  
**Компания**: Александрит  
**Спринт**: 6-й спринт курса Software Architecture


![Built with Love](https://img.shields.io/badge/Built_with-❤️-red)
![Architecture](https://img.shields.io/badge/Architecture-Enterprise-blue)
![Scale](https://img.shields.io/badge/Scale-Production_Ready-green)