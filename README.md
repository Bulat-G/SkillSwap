# SkillSwap

SkillSwap — одностраничное (SPA) приложение, в котором пользователи публикуют навыки двух типов:

- “Учу” — навыки, которыми пользователь готов делиться;
- “Учусь” — навыки, которым пользователь хочет научиться.

Сервис позволяет находить взаимно подходящие пары, отправлять заявки на обмен и вести список текущих/завершённых сессий.

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/6262dd71-39a3-4581-ac86-2f10baf0b2ca" />


## Как поднять проект

### 1. Клонирование репозитория
```bash
git clone https://github.com/PM-YandexPracticum/SkillSwap_36_1.git
cd SkillSwap_36_1
```

### 2. Установка зависимостей
```bash
npm install
```
или
```bash
yarn install
```

### 3. Запуск проекта в режиме разработки
```bash
npm run dev
```

После запуска проект будет доступен по адресу:
```
http://localhost:5173
```
(порт может отличаться, смотри вывод консоли)

### 4. Сборка проекта

```bash
npm run build
```

### 5. Проверка и авто-исправление кода
Линтинг стилей:
```bash
npm run stylelint
npm run stylelint:fix
```

Линтинг кода:
```bash
npm run lint
npm run lint:fix
```

Форматирование кода:
```bash
npm run format
```

Все проверки сразу:
```bash
npm run check
```
