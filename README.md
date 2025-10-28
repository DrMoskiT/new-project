## Developer Guide

### Мета
Налаштувати публічний GitHub-репозиторій `new-project`, створити гілку `development`, додати інструкції та змерджити зміни в `main`.

### Передумови
- Git встановлений локально
- Обліковий запис GitHub
- Доступ: SSH або HTTPS

### Кроки

1. **Створити публічний репозиторій (через GitHub Web)**
   - Перейти: https://github.com/new
   - Назва: `new-project`
   - Visibility: **Public**
   - Без авто-README
   - Create repository

2. **Ініціалізувати локальний репозиторій**
   ```bash
   mkdir -p ~/new-project
   cd ~/new-project
   git init
   git branch -M main
