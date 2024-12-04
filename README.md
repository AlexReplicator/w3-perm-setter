# W3 Perm Setter

[![Version](https://img.shields.io/badge/version-1.0-blue)](https://github.com/AlexReplicator/w3-perm-setter)[![License](https://img.shields.io/badge/license-MIT-green)](https://github.com/AlexReplicator/w3-perm-setter/blob/main/LICENSE)


## Оглавление

- [Описание](https://chat.mistral.ai/chat/ce65b7e5-6995-415f-9863-990456fd7d95#%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5)
- [Подготовительный этап](https://chat.mistral.ai/chat/ce65b7e5-6995-415f-9863-990456fd7d95#%D0%BF%D0%BE%D0%B4%D0%B3%D0%BE%D1%82%D0%BE%D0%B2%D0%B8%D1%82%D0%B5%D0%BB%D1%8C%D0%BD%D1%8B%D0%B9-%D1%8D%D1%82%D0%B0%D0%BF)
  - [Создание нового проекта](https://chat.mistral.ai/chat/ce65b7e5-6995-415f-9863-990456fd7d95#%D1%81%D0%BE%D0%B7%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BD%D0%BE%D0%B2%D0%BE%D0%B3%D0%BE-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0)
  - [Использование существующего проекта](https://chat.mistral.ai/chat/ce65b7e5-6995-415f-9863-990456fd7d95#%D0%B8%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5-%D1%81%D1%83%D1%89%D0%B5%D1%81%D1%82%D0%B2%D1%83%D1%8E%D1%89%D0%B5%D0%B3%D0%BE-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0)
- [Установка](https://chat.mistral.ai/chat/ce65b7e5-6995-415f-9863-990456fd7d95#%D1%83%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BA%D0%B0)
  - [Настройка Git для автоматического преобразования перевода строки](https://chat.mistral.ai/chat/ce65b7e5-6995-415f-9863-990456fd7d95#%D0%BD%D0%B0%D1%81%D1%82%D1%80%D0%BE%D0%B9%D0%BA%D0%B0-git-%D0%B4%D0%BB%D1%8F-%D0%B0%D0%B2%D1%82%D0%BE%D0%BC%D0%B0%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%BE%D0%B3%D0%BE-%D0%BF%D1%80%D0%B5%D0%BE%D0%B1%D1%80%D0%B0%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-%D0%BF%D0%B5%D1%80%D0%B5%D0%B2%D0%BE%D0%B4%D0%B0-%D1%81%D1%82%D1%80%D0%BE%D0%BA%D0%B8)
  - [Добавление в качестве подмодуля Git](https://chat.mistral.ai/chat/ce65b7e5-6995-415f-9863-990456fd7d95#%D0%B4%D0%BE%D0%B1%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5-%D0%B2-%D0%BA%D0%B0%D1%87%D0%B5%D1%81%D1%82%D0%B2%D0%B5-%D0%BF%D0%BE%D0%B4%D0%BC%D0%BE%D0%B4%D1%83%D0%BB%D1%8F-git)
  - [Запуск и конвертирование](https://chat.mistral.ai/chat/ce65b7e5-6995-415f-9863-990456fd7d95#%D0%B7%D0%B0%D0%BF%D1%83%D1%81%D0%BA-%D0%B8-%D0%BA%D0%BE%D0%BD%D0%B2%D0%B5%D1%80%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5)
- [Использование](https://chat.mistral.ai/chat/ce65b7e5-6995-415f-9863-990456fd7d95#%D0%B8%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5)
  - [Запуск скрипта](https://chat.mistral.ai/chat/ce65b7e5-6995-415f-9863-990456fd7d95#%D0%B7%D0%B0%D0%BF%D1%83%D1%81%D0%BA-%D1%81%D0%BA%D1%80%D0%B8%D0%BF%D1%82%D0%B0)
  - [Пример использования](https://chat.mistral.ai/chat/ce65b7e5-6995-415f-9863-990456fd7d95#%D0%BF%D1%80%D0%B8%D0%BC%D0%B5%D1%80-%D0%B8%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F)
- [Обновление и удаление](https://chat.mistral.ai/chat/ce65b7e5-6995-415f-9863-990456fd7d95#%D0%BE%D0%B1%D0%BD%D0%BE%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5-%D0%B8-%D1%83%D0%B4%D0%B0%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5)
  - [Обновление подмодуля](https://chat.mistral.ai/chat/ce65b7e5-6995-415f-9863-990456fd7d95#%D0%BE%D0%B1%D0%BD%D0%BE%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5-%D0%BF%D0%BE%D0%B4%D0%BC%D0%BE%D0%B4%D1%83%D0%BB%D1%8F)
  - [Удаление подмодуля](https://chat.mistral.ai/chat/ce65b7e5-6995-415f-9863-990456fd7d95#%D1%83%D0%B4%D0%B0%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5-%D0%BF%D0%BE%D0%B4%D0%BC%D0%BE%D0%B4%D1%83%D0%BB%D1%8F)
- [Сценарии использования](https://chat.mistral.ai/chat/ce65b7e5-6995-415f-9863-990456fd7d95#%D1%81%D1%86%D0%B5%D0%BD%D0%B0%D1%80%D0%B8%D0%B8-%D0%B8%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F)
- [Лицензия](https://chat.mistral.ai/chat/ce65b7e5-6995-415f-9863-990456fd7d95#%D0%BB%D0%B8%D1%86%D0%B5%D0%BD%D0%B7%D0%B8%D1%8F)

## Описание

**W3 Perm Setter** — это Bash-скрипт, который позволяет настроить права доступа и владельца папки, чтобы можно было адекватно работать с проектом на локальном сервере.

## Подготовительный этап

### Создание нового проекта

Если ваш проект еще не создан и не подключен к Git:

``
```
mkdir -p /path/to/your/project/ 
cd /path/to/your/project/ 
git init
```

### Использование существующего проекта

Если проект уже создан и подключен к Git:

`cd /path/to/your/project/`

## Установка

Рекомендуется разместить скрипт в директории `./scripts/` вашего проекта:

```
mkdir -p scripts cd scripts
```

### Настройка Git для автоматического преобразования перевода строки

Создайте файл `.gitattributes` в корневой директории проекта с следующим содержимым:

```
* text=auto
```

### Добавление в качестве подмодуля Git

Чтобы добавить **W3 Perm Setter** в свой проект в качестве подмодуля, выполните:

`git submodule add https://github.com/AlexReplicator/w3-perm-setter.git scripts/w3-perm-setter`

### Запуск и конвертирование

Нужно установить `dos2unix` и преобразовать файл. Это можно сделать так:

```
sudo apt install dos2unix 
dos2unix scripts/w3-perm-setter/set.sh
```

Сделайте файл скрипта исполняемым:

`chmod +x scripts/w3-perm-setter/set.sh`

## Использование

### Запуск скрипта

Для запуска скрипта выполните следующую команду:

`./scripts/w3-perm-setter/set.sh /path/to/your/project`

### Пример использования

Пример использования скрипта для настройки прав доступа и владельца папки:

`./scripts/w3-perm-setter/set.sh ../../project`

## Обновление и удаление

### Обновление подмодуля

#### Все подмодули

Для обновления всех подмодулей до последней версии:

`git submodule update --init --recursive`

#### Только этот подмодуль

Для обновления только этого подмодуля:

```
git submodule update --init --recursive scripts/w3-perm-setter 
git submodule status scripts/w3-perm-setter 
cd scripts/w3-perm-setter 
git pull origin main
```

### Удаление подмодуля

Для удаления подмодуля выполните следующие команды:

```
git submodule deinit -f scripts/w3-perm-setter 
rm -rf .git/modules/scripts/w3-perm-setter git 
rm -f scripts/w3-perm-setter 
git commit -m "Removed w3-perm-setter submodule" 
rm -rf scripts/w3-perm-setter
```

## Сценарии использования

**W3 Perm Setter** может быть полезен в следующих сценариях:

1. **Настройка нового проекта**: Быстро настроить права доступа и владельца для нового проекта.
2. **Обновление существующего проекта**: Обновить права доступа и владельца для существующего проекта после изменений.
3. **Работа в команде**: Обеспечить единообразные права доступа и владельца для всех участников команды.

## Лицензия

Этот проект лицензирован под [MIT License](https://github.com/AlexReplicator/w3-perm-setter/blob/main/LICENSE).