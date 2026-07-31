# Vector Role

Устанавливает и настраивает Vector на CentOS 7.

## Переменные

| Переменная | По умолчанию | Описание |
|---|---|---|
| vector_version | 0.33.0 | Версия Vector |
| vector_arch | x86_64 | Архитектура пакета |

## Зависимости

Нет.

## Пример использования

    - hosts: vector
      roles:
        - vector-role
