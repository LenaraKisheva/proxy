# Перехват трафика через Charles Proxy

Используя Charles Proxy, я протестировала корзину интернет-магазина <a href="https://demowebshop.tricentis.com/cart"> demowebshop</a>  в Google Chrome на Macbook Air:

<ul>
  <li>  <a href="https://drive.google.com/file/d/1UZjl-q_QJajh7zXKXK8PyStJEobzWRfz/view?usp=sharing">
  Изменение количеств товаров</a> в корзине (в запросе отправляется "2 товара", а вы должны вернуть "500")</li>
  <li>  <a href="https://drive.google.com/file/d/1AxWpBXh8b4orq0R9JlZ1Di0iuqzCxuaZ/view?usp=sharing">
  Ситуация </a> , при которой сервер вернет статус-код 403  </li>
  <li>  <a href="https://drive.google.com/file/d/1lUBmPvCm5p2De2yD35dfQgedHGHxXumz/view?usp=sharing">
  Перенаправление запроса с Prod на QA </a> </li>
</ul>

---

Используя Charles Proxy, я протестировала на мобильном телефоне интернет-магазин <a href="https://demowebshop.tricentis.com/cart"> demowebshop</a> в Safari на iPhone:

<ul>
  <li>  <a href="https://drive.google.com/file/d/1e_Ji6_1xE1COdjQUBz1S5_yZKh85qt5P/view?usp=sharing">
  Удаление товаров</a> в корзине</li>
  <li>  <a href="https://drive.google.com/file/d/14iKezF4Nl3Xi4ZYRX6QE42DCFI4ov2Pg/view?usp=sharing">
  Замена сайта картинкой</a></li>
  <li>  <a href="https://drive.google.com/file/d/1_xeQiDhBgSaaCT4KfokONP1QJGuIsx3W/view?usp=sharing">
  Перехваченный HTTPs-запроса с мобильного устройства</a>(В header user-agent должна быть информация о устройстве.) </li>
</ul>
