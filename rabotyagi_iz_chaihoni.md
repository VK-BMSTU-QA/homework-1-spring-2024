# Теги
## Положительные кейсы

1. **Создание поста с одним тегом**: 
![oneTagCheck](/static/tags/oneTagCheck.png) 
**Результат**: создается пост с одним тегом, который виден автору:
![oneTagResult](/static/tags/oneTagResult.png)
2. **Создание поста с несколькими тегами**:
![muchTagsCheck](/static/tags/muchTagsCheck.png)
**Результат**:
![muchTagsResult](/static/tags/muchTagsResult.png)
3. **Добавим много пробелов в названии тега**:
![oneTagSpaceCheck](/static/tags/oneTagSpaceCheck.png)
**Резльтат** (отображается без лишних пробелов):
![oneTagSpaceCheck](/static/tags/oneTagSpaceCheck.png)
4. **Производим переход по тегу**:
![goToTagCheck](/static/tags/goToTagCheck.png)
**Результат**:
![goToTagResult](/static/tags/goToTagResult.png)
5. **Регистрируемся или автроризуемся за донатера, пытаемся посмотреть его ленту по тегу**:
![findTagCheck](/static/tags/findTagCheck.png)
**Результат**:
![findTagResult](/static/tags/findTagResult.png)

## Баги
1. **Неправильная дата в ленте по тегам**:
![badDateBug](/static/tags/badDateBug.png) 
2. **Недетерминированный порядок тегов в посте (скорее недостаток), пример до и после перезагрузки страницы**:
![wrongOrderTags1](/static/tags/wrongOrderTags1.png) 
![wrongOrderTags2](/static/tags/wrongOrderTags2.png)
3. **Недетерминированный порядок постов в ленте по тегам (нет сортировки по дате)**:
![wrongPostsOrder1](/static/tags/wrongPostsOrder1.png)
![wrongPostsOrder2](/static/tags/wrongPostsOrder2.png)
4. **Поплыла верстка navbara на mozilla**:
![badNavbar](/static/tags/badNavbar.png)
5. **Сломанный поиск по тегам для аккаунтов не автора (не отображается список постов по тегу у донатера в ленте постов по тегу)**:
![wrongSearch1](static/tags/wrongSearch1.png)
![wrongSearch2](static/tags/wrongSearch2.png)

## Негативные кейсы
1. **Ввод zalgo текста в названии тега**:
![zalgoCheck](/static/tags/zalgoCheck.png)
**Результат**:
![zalgoResult](/static/tags/zalgoResult.png)
2. **Попытка js-инъекции**:
![jsInjCheck](/static/tags/jsInjCheck.png)
**Результат (код не отработал)**:
![jsInjResult](/static/tags/jsInjResult.png)