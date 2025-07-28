# 🛒🛍️ Тестирование API веб-приложения Яндекс Прилавка
Яндекс.Прилавка — это интернет-магазин, где можно купить разные товары. Это как обычный магазин, только в интернете.
Чтобы купить что-то на Яндекс.Прилавке, нужно:
* найти товар на сайте или в приложении
* выбрать его и положить в корзину
* оформить заказ
* получить товар с ближайшего склада
  
Яндекс.Прилавка работает с разными магазинами, чтобы у пользователей был большой выбор товаров. Магазины отправляют свои товары на склады Яндекс.Прилавки, откуда их забирают покупатели.

<a href="https://code.s3.yandex.net/qa/files/backend_requirements.pdf">_Требования к бэкенду приложения_</a>

В рамках учебного проекта нужно было выполнить 4 задания:

* Проанализировать требования к новой функциональности бэкенда Яндекс.Прилавка  
* Изучить документацию к API в Apidoc  
* Спроектировать тесты в виде чек-листа, чтобы покрыть новую функциональность  
_-Работа с наборами: возможность добавлять продукты в набор_    
Ручка **POST /api/v1/kits/:id/products**;   
_-Работа с курьерами: возможность проверить, есть ли доставка курьерской службой «Привезём быстро» и сколько она стоит_  
Ручка **POST /fast-delivery/v3.1.1/calculate-delivery.xml**;   
_-Работа с корзиной:_  
  возможность получить список продуктов, которые добавили в корзину    
  _Ручка **GET /api/v1/orders/:id**_  
  возможность добавлять продукты в корзину  
  _Ручка **PUT /api/v1/orders/:id**_  
  возможность удалять корзину  
  _Ручка **DELETE /api/v1/orders/:id**_  
* Протестировать API через Postman и завести баг-репорты


# ✨Выполнение
<a href="https://docs.google.com/document/d/161Fx4IdkftuBroqNpaibnIktY8SrgQnElKLzegX_ssw/edit?usp=sharing">_Полный документ по проекту_</a>

1. Составил <a href="https://docs.google.com/spreadsheets/d/1CQAbk9FgTTduBCgiPpIPmBg8pTynKrxjyoYuXqZuSO8/edit?gid=0#gid=0">тестовую документацию</a> для API
   <details>
  	       <summary>Фрагмент документации</summary>
              
	![Описание изображения](https://github.com/Art8m1s/QA-YA-Prilavok_api/blob/main/listchek.png)

  	</details>
2. Протестировал API через Postman
   <details>
  	       <summary>Фрагмент скринов из Postman</summary>
              
	![Описание изображения](https://github.com/Art8m1s/QA-YA-Prilavok_api/blob/main/24.png)
  ![Описание изображения](https://github.com/Art8m1s/QA-YA-Prilavok_api/blob/main/28.png)
  ![Описание изображения](https://github.com/Art8m1s/QA-YA-Prilavok_api/blob/main/8.png)

  </details>
   
3. Завел найденные баги в <a href="https://docs.google.com/spreadsheets/d/1CQAbk9FgTTduBCgiPpIPmBg8pTynKrxjyoYuXqZuSO8/edit?gid=1673303584#gid=1673303584">документе</a>
   <details>
  	       <summary>Фрагмент баг репорта</summary>
              
	![Описание изображения](https://github.com/Art8m1s/QA-YA-Prilavok_api/blob/main/bugrep.png)

  	</details>
