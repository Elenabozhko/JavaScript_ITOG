# JavaScript_ITOG
ITOG
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.2/css/all.min.css" integrity="sha512-HK5fgLBL+xu6dm/Ii3z4xhlSUyZgTT9tuc/hSrtw6uzJOvgRr2a9jyxxT1ely+B+xFAmJKVSTbpM/CuL7qxO8w==" crossorigin="anonymous" />
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <div class="header">
        <div class="container">
            <div class="leftHeader">
                <img src="images/logo.png" alt="">
                <img class="searchIcon" src="images/search.png" alt="">
            </div>

            <div class="rightHeader">
                <img src="images/bars.png" alt="">
                <img class="userIcon" src="images/user.png" alt="">

                <span class="cartIconWrap">
                    <img class="cartIcon" src="images/cart.png" alt="">
                    <span>0</span>
                </span>

                <div class="basket hidden">
                    <div class="basketRow basketHeader">
                        <div>Название товара</div>
                        <div>Количество</div>
                        <div>Цена за шт.</div>
                        <div>Итого</div>
                    </div>

                    <div class="basketTotal">
                        Товаров в корзине на сумму:
                        $<span class="basketTotalValue">0</span>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div class="newArrivals">
        <div class="container">
            <h1>NEW COLLECTION</h1>
            <nav>
                <a href="#">HOME</a>
                <span>/</span>
                <a href="#">MEN</a>
                <span>/</span>
		<a href="#">WOMEN</a>
                <span>/</span>
                <a href="#">NEW COLLECTION</a>
            </nav>
        </div>
    </div>

    <div class="filters">
        <div class="container">
            <div class="filtersLeft">
                <span class="filterLabel">Фильтр</span>
                <img class="filterIcon" src="images/filter.svg" alt="">
                <div class="filterPopup hidden">
                    <nav class="filterCategory">
                        <div class="filterCategoryHeader">КАТЕГОРИЯ</div>
                        <div class="hidden">
                            <a href="#">Аксессуары</a>
                            <a href="#">Сумки</a>
                            <a href="#">Джинсы</a>
                            <a href="#">Толстовки и свитера</a>
                            <a href="#">Куртки и пальто</a>
                            <a href="#">Рубашки</a>
                            <a href="#">Обувь</a>
                            <a href="#">Трикотаж</a>
                            <a href="#">Футболки</a>
                        </div>
                    </nav>
                </div>
            </div>
            <div class="filtersRight">
                <div class="filterTrending">
                    В наличии
                    <img src="images/filterArrow.svg" alt="">
                </div>
                <div class="filterSize">
                    <div class="filterSizeWrap">
                        Размеры
                        <img src="images/filterArrow.svg" alt="">
                    </div>
                    <div class="filterSizes hidden">
                        <div>
                            <input type="checkbox"> XS
                        </div>
                        <div>
                            <input type="checkbox"> S
                        </div>
                        <div>
                            <input type="checkbox"> M
                        </div>
                        <div>
                            <input type="checkbox"> L
                        </div>
                    </div>
                </div>
                <div class="filterPrice">
                    Цена
                    <img src="images/filterArrow.svg" alt="">
                </div>
            </div>
        </div>
    </div>

    <div class="featured container">
        <h2 class="featuredHeader">Каталог</h2>
        <div class="featuredTitle">Новая коллекция</div>

        <div class="featuredItems">
            <div class="featuredItem" data-id="1" data-name="Rafaelli Рюкзак" data-price="15">
                <div class="featuredImgWrap">
                    <img src="images/featured/1.jpg" alt="">
                    <div class="featuredImgDark">
                        <button class="addToCart">
                            <img src="images/cart.svg" alt="">
                            Add to Cart
                        </button>
                    </div>
                </div>

                <div class="featuredData">
                    <div class="featuredName">
                        Rafaelli Рюкзак
                    </div>
                    <div class="featuredText">
                        Вещи молодого дизайнера из России, созданные из лучших европейских тканей.
                    </div>
                    <div class="featuredPrice">
                        $15.00
                    </div>
                </div>
            </div>

            <div class="featuredItem" data-id="2" data-name="Rafaelli Костюм" data-price="320">
                <div class="featuredImgWrap">
                    <img src="images/featured/2.jpg" alt="">
                    <div class="featuredImgDark">
                        <button class="addToCart">
                            <img src="images/cart.svg" alt="">
                            Add to Cart
                        </button>
                    </div>
                </div>

                <div class="featuredData">
                    <div class="featuredName">
                        Rafaelli Костюм
                    </div>
                    <div class="featuredText">
                        Вещи молодого дизайнера из России, созданные из лучших европейских тканей.
                    </div>
                    <div class="featuredPrice">
                        $320.00
                    </div>
                </div>
            </div>

            <div class="featuredItem" data-id="3" data-name="Rafaelli Толстовка" data-price="195">
                <div class="featuredImgWrap">
                    <img src="images/featured/3.jpg" alt="">
                    <div class="featuredImgDark">
                        <button class="addToCart">
                            <img src="images/cart.svg" alt="">
                            Add to Cart
                        </button>
                    </div>
                </div>

                <div class="featuredData">
                    <div class="featuredName">
                        Rafaelli Толстовка
                    </div>
                    <div class="featuredText">
                        Вещи молодого дизайнера из России, созданные из лучших европейских тканей.
                    </div>
                    <div class="featuredPrice">
                        $195.00
                    </div>
                </div>
            </div>

            <div class="featuredItem" data-id="4" data-name="Rafaelli Джинсы" data-price="260">
                <div class="featuredImgWrap">
                    <img src="images/featured/4.jpg" alt="">
                    <div class="featuredImgDark">
                        <button class="addToCart">
                            <img src="images/cart.svg" alt="">
                            Add to Cart
                        </button>
                    </div>
                </div>

                <div class="featuredData" data-id="3" data-name="Rafaelli Рюкзак" data-price="15">
                    <div class="featuredName">
                        Rafaelli Джинсы
                    </div>
                    <div class="featuredText">
                        Вещи молодого дизайнера из России, созданные из лучших европейских тканей.
                    </div>
                    <div class="featuredPrice">
                        $260.00
                    </div>
                </div>
            </div>

            <div class="featuredItem" data-id="5" data-name="Rafaelli Пиджак" data-price="170">
                <div class="featuredImgWrap">
                    <img src="images/featured/5.jpg" alt="">
                    <div class="featuredImgDark">
                        <button class="addToCart">
                            <img src="images/cart.svg" alt="">
                            Add to Cart
                        </button>
                    </div>
                </div>

                <div class="featuredData">
                    <div class="featuredName">
                        Rafaelli Пиджак
                    </div>
                    <div class="featuredText">
                        Вещи молодого дизайнера из России, созданные из лучших европейских тканей.
                    </div>
                    <div class="featuredPrice">
                        $170.00
                    </div>
                </div>
            </div>

            <div class="featuredItem" data-id="6" data-name="Rafaelli Рубашка" data-price="85">
                <div class="featuredImgWrap">
                    <img src="images/featured/6.jpg" alt="">
                    <div class="featuredImgDark">
                        <button class="addToCart">
                            <img src="images/cart.svg" alt="">
                            Add to Cart
                        </button>
                    </div>
                </div>

                <div class="featuredData">
                    <div class="featuredName">
                        Rafaelli Рубашка
                    </div>
                    <div class="featuredText">
                        Вещи молодого дизайнера из России, созданные из лучших европейских тканей.
                    </div>
                    <div class="featuredPrice">
                        $85.00
                    </div>
                </div>
            </div>
        </div>

        <div class="pagination">
            <a href="#">
                <img src="images/chevronLeft.svg" alt="">
            </a>
            <a href="#">1</a>
            <a href="#">2</a>
            <a href="#">3</a>
            <a href="#">4</a>
            <a href="#">5</a>
            <a href="#">6.....20</a>
            <a href="#">
                <img src="images/chevronRight.svg" alt="">
            </a>
        </div>
    </div>

    <div class="services">
        <div class="container">

            <div class="serivceUnit">
                <img src="images/services/delivery.svg" alt="">
                <div class="servicesTitle">
                    Доставка
                </div>
                <div class="servicesText">
                   Доставка по всей России.
                </div>
            </div>

            <div class="serivceUnit">
                <img src="images/services/discount.svg" alt="">
                <div class="servicesTitle">
                   Акции
                </div>
                <div class="servicesText">
                    Действуют для всех покупателей.
                </div>
            </div>

            <div class="serivceUnit">
                <img src="images/services/assurance.svg" alt="">
                <div class="servicesTitle">
                   Гарантия качества
                </div>
                <div class="servicesText">
                   Используются лучшие материалы Европы.
                </div>
            </div>
        </div>
    </div>

    <div class="subscribe">
        <div class="container">

            <div class="subscribeRight">
                <div class="subscribeTitle">
                    Подпишись
                </div>
                <div class="subscribeText">
                    Для получения обновление коллекции и размеров
                </div>
                <form action="" class="Форма подписки">
                    <input type="text" placeholder="Введите свой адрес электронной почты">
                    <button>Subscribe</button>
                </form>
            </div>

        </div>
    </div>

    <div class="footer">
        <div class="container">
            <div class="footerLeft">
                <a href="#">
                    <i class="fab fa-facebook-f"></i>
                </a>
                <a href="#">
                    <i class="fab fa-instagram"></i>
                </a>
                <a href="#">
                    <i class="fab fa-twitter"></i>
                </a>
            </div>
            <div class="footerRight">
                &copy; 2022  Rafaelli_brand  All Rights Reserved.
            </div>
        </div>
    </div>

    <script src="app.js"></script>
    <script src="basket.js"></script>
</body>

</html>
