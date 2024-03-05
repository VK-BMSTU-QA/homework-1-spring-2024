## Главная страница

[Главная страница](https://zuzu-market.ru)

![image](https://github.com/khristina455/homework-1-spring-2024/assets/63557586/c8a493f2-d617-4ae1-826c-c43810c5e6cf)

**Положительные тесты**

1. Карточки товаров пролистываются с плавной анимацией при каждом нажатии на слайдеры каруселей и самостоятельно не возращаются в исходное состояние.
2. Каждая карточка карусели содержит название, которое помещается целиком, если меньше 2 строчек в высоту и обрезается тремя точками в конце, если больше двух строк в высоту.
3. В каждой карточке возможен переход на страницу Товара при клике на Фото, Название.

   ![image](https://github.com/khristina455/homework-1-spring-2024/assets/63557586/9b6e570c-b287-41dd-be41-777134accea3)

4. В каждой карточке возможен переход на страницу отзывов при клике на "Звездочку" с общим рейтингом и количество отзывов.

   ![image](https://github.com/khristina455/homework-1-spring-2024/assets/63557586/de863e71-eeca-462f-9cc8-d80d92d1e1cf)

5. При клике на кнопку "В корзину" отображается счетчик количества данного товара, добавленного в корзину. Также в хедере отображается счетчик количества всех товаров в корзине.

   ![image](https://github.com/khristina455/homework-1-spring-2024/assets/63557586/db99ca30-335d-47c4-9c1a-2cb7329fa9b0)

   ![image](https://github.com/khristina455/homework-1-spring-2024/assets/63557586/a56e4703-0969-46ab-ad17-33dfbc2ee304)

6. При клике на "Минус" в карточке товара, когда счетчик добавленного товара в корзину равен единице, появляется кнопка "В корзину".

   ![image](https://github.com/khristina455/homework-1-spring-2024/assets/63557586/bd8c6b26-d9c4-4708-9ea3-a8cd66b42f86)
   ![image](https://github.com/khristina455/homework-1-spring-2024/assets/63557586/608cd74c-4eb3-4e92-820b-f950760ce26a)


**Негативные тесты**

1. При первом клике на правые слайдеры в каждой из карусель, когда они расположены в исходном состоянии, карточка товара пролистывается на одну больше.

   ![image](https://github.com/khristina455/homework-1-spring-2024/assets/63557586/406cf9b0-03b3-4819-b8ff-d354eaf44f8f)

2. При попытке добавить более 100 товаров - появляется окно, что можно добавить не больше 100 позиций.

   ![image](https://github.com/khristina455/homework-1-spring-2024/assets/63557586/ccb6662c-7d19-4849-9b4a-dcfbc1c6554f)

3. При масштабе 80% иногда появляется часть 3 строки в названии товара.

   ![image](https://github.com/khristina455/homework-1-spring-2024/assets/63557586/2291625f-0979-457c-878b-f6a64a6959c9)

---

##  Каталог

[Каталог](https://zuzu-market.ru)

![image](https://github.com/khristina455/homework-1-spring-2024/assets/63557586/1d76051a-2aa3-461f-ba65-c2918692404a)

**Положительные тесты**

1. При клике на "Каталог" выпадает список категорий, который открывается поверх главной страницы.
2. При открытом каталоге и клике на кнопку "Каталог с крестиком" происходит закрытие каталога.

3. При наведении на название категории меняется цвет шрифта.

   ![image](https://github.com/khristina455/homework-1-spring-2024/assets/63557586/c699225c-281d-4675-9313-efee65e38bb7)
   ![image](https://github.com/khristina455/homework-1-spring-2024/assets/63557586/4f963674-3522-4972-b5c3-e574957746fa)


**Негативные тесты**

1. При обновлении страницы каталог закрывается.

---

##  Сортировка

[Сортировка](https://zuzu-market.ru/category/31)

![image](https://github.com/khristina455/homework-1-spring-2024/assets/63557586/8e2b1397-d31a-4c37-8efc-99dd82020ade)

**Положительные тесты**

1. При клике на поле с названием сортировки, установленной по умолчанию, отображается меню с выбором доступных сортировок: "По популярности", "По уменьшению цены", "По возрастанию цены", "По рейтингу".

   ![image](https://github.com/khristina455/homework-1-spring-2024/assets/63557586/ffcbc155-cdf5-4435-a4c5-062345d63c7f)

**Негативные тесты**

1. При обновлении страницы слетает выбранный тип сортировки и устанавливается "По популярности".

   ![image](https://github.com/khristina455/homework-1-spring-2024/assets/63557586/16eba510-fa66-4d25-851f-08360fc19fba)

---

##  Профиль пользователя(адрес)

[Профиль пользователя(адрес)](https://zuzu-market.ru/my-profile)

![image](https://github.com/khristina455/homework-1-spring-2024/assets/63557586/2fb513c4-aefa-4926-9d36-fd55cf467d80)

**Положительные тесты**

1. При клике на кнопку "Добавить" отрисовывается кнопка "Сохранить" и поля для ввода: Города, Улицы, Дома, Квартиры.

   ![image](https://github.com/khristina455/homework-1-spring-2024/assets/63557586/4e6937eb-9246-43b2-9bb2-d4518b333ed7)

2. При нажатии на кнопку "Сохранить" появляется сообщении заполнить обязательные пустые поля.

   ![image](https://github.com/khristina455/homework-1-spring-2024/assets/63557586/b02e6c90-73f6-4fe1-a40a-b72d2adbc086)

3. Каждый новый введенный адрес автоматически становится текущим адресом доставки.

   ![image](https://github.com/khristina455/homework-1-spring-2024/assets/63557586/37f50bbe-d7fe-4935-8652-ba74913c2c09)
   ![image](https://github.com/khristina455/homework-1-spring-2024/assets/63557586/1deebed7-2255-49e0-ade2-f9090fbabf31)

4. При клике на кнопку "Выбрать текущим" адрес переходит в начало списка.

   ![image](https://github.com/khristina455/homework-1-spring-2024/assets/63557586/1deebed7-2255-49e0-ade2-f9090fbabf31)
   ![image](https://github.com/khristina455/homework-1-spring-2024/assets/63557586/e00cbdf3-7779-4993-a810-312d99c1e149)

5. При нажатии на "Ручку" можно изменить как текущие, так и остальные адреса.

   ![image](https://github.com/khristina455/homework-1-spring-2024/assets/63557586/94674fb4-a2f6-4008-8d0b-aacb827fcafa)
   ![image](https://github.com/khristina455/homework-1-spring-2024/assets/63557586/a903e022-c03c-446d-a504-1e721dd64dbe)
   ![image](https://github.com/khristina455/homework-1-spring-2024/assets/63557586/0e993f49-ce74-47ed-9900-161876e10d03)

6. При редактировании адреса нельзя оставить обязательные поля пустыми, действуют те же правила валидации, что и во время добавления адреса.

   ![image](https://github.com/khristina455/homework-1-spring-2024/assets/63557586/211d89d8-f16c-4159-8fe6-5c3f9657bac4)

7. Поле "Квартира" не является обязательным и может остаться незаполненым.

   ![image](https://github.com/khristina455/homework-1-spring-2024/assets/63557586/0f489eab-8254-41b1-91a2-5f36e2b9f393)
   ![image](https://github.com/khristina455/homework-1-spring-2024/assets/63557586/ab6e0c77-695f-4bc5-bb6a-e80d360efb99)


**Негативные тесты**

1. При обновлении страницы закрывается выбранная вкладка профиля "Мои адреса" и открывается вкладка "Мои данные", также пропадают введенные несохраненные данные о адресе доставки.

2. Нет ограничений на ввод цифр и букв в каждое из полей адреса.

   ![image](https://github.com/khristina455/homework-1-spring-2024/assets/63557586/1a72f61a-b860-4630-b849-cfc2809d5203)
   ![image](https://github.com/khristina455/homework-1-spring-2024/assets/63557586/d21e2444-1850-46b8-835c-640b54385ae0)

3. Нельзя удалить текущий адрес, его можно только заменить на другой и только потом удалить.

   ![image](https://github.com/khristina455/homework-1-spring-2024/assets/63557586/e00cbdf3-7779-4993-a810-312d99c1e149)

4. Можно добавить два одинаковых адреса.

   ![image](https://github.com/khristina455/homework-1-spring-2024/assets/63557586/3065a8b5-b157-4c96-9393-121917b03ac9)

5. Нет ограничений на количество добавленных адресов.

6. Если введен только один адрес, то его нельзя удалить, можно только изменить.

   ![image](https://github.com/khristina455/homework-1-spring-2024/assets/63557586/53aa0b6b-a159-4f50-a1ed-51b083bc4549)

