# 🍽️ Foodgram — продуктовый помощник

## 📌 Описание
Foodgram — это веб-приложение для публикации рецептов, подписки на авторов и формирования списка покупок.

Пользователи могут создавать рецепты, добавлять ингредиенты, подписываться на других авторов и скачивать список покупок для выбранных рецептов.

---

## 🚀 Функциональность

- Регистрация и аутентификация пользователей  
- Создание, редактирование и удаление рецептов  
- Добавление рецептов в избранное  
- Подписка на авторов  
- Формирование списка покупок  
- Скачивание списка покупок в текстовом формате  

---

## 🛠️ Стек технологий

- Python  
- Django  
- Django REST Framework  
- PostgreSQL  
- Docker  
- Nginx  

---

## ⚙️ Запуск проекта

```bash
git clone https://github.com/eqsx000111/foodgram.git
cd foodgram
```

Создать и заполнить .env
```bash
docker-compose up -d
```
Применить миграции:
```bash
docker-compose exec backend python manage.py migrate
```
Создать суперпользователя:
```bash
docker-compose exec backend python manage.py createsuperuser
```

---

## 📂 Структура проекта
	-	backend/ — серверная часть Django
	-	frontend/ — клиентская часть
	-	infra/ — конфигурация Docker и Nginx

---

## 👤 Автор
**GitHub:** [eqsx000111](https://github.com/eqsx000111)

**Email:** [deddotu@yandex.ru](mailto:deddotu@yandex.ru)

**Telegram:** @eqsx1

**Phone number:** 89787172691

**ФИО:** Ильницкий Иван Александрович 
