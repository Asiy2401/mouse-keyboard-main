# Диаграмма сгорания Спринта 1 (01.05 - 04.05.2025)

```mermaid
gantt
    title Спринт 1: Базовый каркас (20 SP)
    dateFormat  YYYY-MM-DD
    axisFormat %d.%m
    todayMarker 2025-05-22
    
    section План
    Полный спринт (План) :done, 2025-02-17, 2025-03-03
    
    section Факт
    Инициализация (2 SP) :done, 2025-05-01, 1d
    Подключение кода (5 SP) :done, 2025-05-02, 1d
    Настройка FSM (3 SP) :active, 2025-05-03, 1d
    Трекинг (4 SP) :crit, 2025-05-04, 1d
    
    section Прогресс
    Выполнено : 10, 2025-05-01, 2025-05-02
    Осталось : 10, after 2025-05-02, 2d
