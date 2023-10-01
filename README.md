# simplebuy


Установить Docker Desktop (https://www.docker.com/products/docker-desktop/);  

Скачать проект; 
Открыть его в вашей IDE; 
Перейти в папку project; 
Открыть терминал; 
Сбилдить образ через команду: docker-compose build; 
Поднять контейнер через команду: docker-compose up; 
Открыть браузер и перейти на страницу: http://127.0.0.1:8000/; 
Залогиниться под суперюзером с помощью кнопки "Log In";
Перейти на страницу http://127.0.0.1:8000/api/v1/products/ для получения списка товаров;
Перейти на страницу http://127.0.0.1:8000/api/v1/products/int:pk/ для работы с отдельным товаром;
Перейти на страницу http://127.0.0.1:8000/api/v1/carts/ и отправить POST запрос -> создастся ваша корзина;
Перейти на страницу http://127.0.0.1:8000/api/v1/carts/int:id_your_cart/items/ ввести id товара и его количество -> этот товар добавится в корзину;
Вернуться на страницу http://127.0.0.1:8000/api/v1/carts/int:id_your_cart/items/ и посмотреть список товаров в корзине;
Перейти на страницу http://127.0.0.1:8000/api/v1/orders/ ввести id корзины -> создатся ваш заказ, вы сможете посмотреть список всех ваших заказов и их содержимое, очистится ваша корзина;
