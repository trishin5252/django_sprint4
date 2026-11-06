# Блогикум — формы, пользователи и комментарии

Готовый Django-проект находится в архиве [blogicum-forms-complete.zip](blogicum-forms-complete.zip). Скачайте и распакуйте архив: все исходники, миграции, шаблоны и тесты находятся в папке django_sprint4. Шаблоны Практикума сохранены без изменений.

## Запуск

Рекомендуется Python 3.10.

```sh
python -m venv venv
# Windows: venv\Scripts\activate
pip install -r requirements.txt
cd blogicum
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver --insecure
```

Для разработки установите DEBUG = True в blogicum/settings.py.
Пользовательские изображения сохраняются в media/, письма — в sent_emails/.
