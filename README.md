![example workflow](https://github.com/AnastasiaPanevskaya/yamdb_final/actions/workflows/yamdb_workflow.yml/badge.svg)  
# Учебный проект API для модулей приложения YaTube  
REST API проект для сервиса YaMDb — сбор отзывов о фильмах, книгах или музыке.  

Документация по проекту доступна по адресу: http://84.201.132.80/redoc/  
Адрес сайта доступен по ссылке: http://84.201.132.80/admin/  

## Как запустить проект:  

### Клонируем репозиторий и заходим в него через терминал:  

git clone git@github.com:AnastasiaPanevskaya/yamdb_final.git  
cd yamdb_final  
cd api_yamdb  

###
Как зарегистрировать пользователя:  
1.Сделайте POST запрос, укаказав в теле "username" и "email" на эндпоинт "api/v1/auth/signup/"  
2.YaMDb отправит проверочный код на указанный email  
3.Сделайте POST запрос указав "email" и "confirmation_code" в теле запроса на эндпоинт "api/v1/auth/token/"/,в ответе вы получите JWT-токен  
