# Python CI/CD Pipeline

Лабораторная работа: настройка пайплайна CI/CD для Python-приложения с использованием GitHub Actions и Docker.

## 1. Локальная сборка Docker
Приложение успешно собирается и запускается в контейнере.
**<img width="460" height="72" alt="изображение" src="https://github.com/user-attachments/assets/a0ce6f1e-1570-44c4-8da9-ff739a0387b7" />
**

## 2. Успешный запуск пайплайна (GitHub Actions)
Пайплайн запускается при пуше и включает в себя тестирование (на версиях Python 3.10, 3.11, 3.12) и сборку Docker-образа. Все джобы завершились успешно.
**<img width="607" height="172" alt="изображение" src="https://github.com/user-attachments/assets/3bffe57e-d7a9-4ed8-9650-ab08bc91787a" />
**

## 3. Логи линтинга и тестирования
В джобе `Lint & Test` успешно пройдена проверка стиля кода (`flake8`) и запущены тесты (`pytest`).
**<img width="590" height="320" alt="изображение" src="https://github.com/user-attachments/assets/750c9997-575b-4458-b3d0-56a708caf74c" />
**
**<img width="597" height="287" alt="изображение" src="https://github.com/user-attachments/assets/c2706d66-678d-45b1-b434-23ff686659d0" />
 />
**

## 4. Логи сборки Docker-образа
Джоб `Build Docker Image` успешно собрал образ приложения в среде CI.
**<img width="579" height="229" alt="изображение" src="https://github.com/user-attachments/assets/1e8fca91-6e45-44b9-90f3-eab284412ebf" />
**

## Вывод
В ходе работы был настроен полный цикл CI для Python-приложения. Автоматизированы проверки кода, тестирование и сборка Docker-образа. Все задачи выполнены.
