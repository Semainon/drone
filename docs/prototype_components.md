
```markdown
# Компоненты прототипа
## 1. Мобильное приложение (Flutter)
### Core Components
```dart
// lib/core/
├── mavlink/
│   ├── parser.dart      # Парсинг MAVLink сообщений
│   ├── commander.dart   # Отправка команд
│   └── types.dart       # MAVLink типы данных
├── maps/
│   ├── drone_map.dart   # Карта с overlay дрона
│   ├── mission_layer.dart # Отображение миссии
│   └── geofence_layer.dart # Геозоны
└── telemetry/
    ├── dashboard.dart   # Панель телеметрии
    ├── charts.dart      # Графики в реальном времени
    └── logger.dart      # Логирование