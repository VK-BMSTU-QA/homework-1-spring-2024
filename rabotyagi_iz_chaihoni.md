# Теги
## Положительные кейсы
- создание поста с одним тегом: 
![alt text](/static/tags/image.png)
- результат:
создается пост с одним тегом, который виден автору:
![alt text](/static/tags/image-1.png)
- cоздание поста с несколькими тегами:
![alt text](/static/tags/image-2.png)
- результат:
![alt text](/static/tags/image-3.png)
- создание поста без тегов:
![alt text](/static/tags/image-4.png)
- результат:
- добавим много пробелом в названии тега:
![alt text](/static/tags/image-21.png)
- резльтат (корректно отображается):
![alt text](/static/tags/image-22.png)
![alt text](/static/tags/image-6.png)
- производим переход по тегу:
![alt text](/static/tags/image-11.png)
- результат:
![alt text](/static/tags/image-12.png)
- регистрируемся за гостя, пытаемся посмотреть его ленту по тегу:
![alt text](/static/tags/image-19.png)
- результат:
![alt text](/static/tags/image-20.png)

## Баги
- неправильная дата в ленте по тегам:
![alt text](/static/tags/image-13.png) 
- недетерминированный порядок тегов в посте (скорее недостаток):
![alt text](/static/tags/image-14.png) 
![alt text](/static/tags/image-15.png)
- недетерминированный порядок постов в ленте по тегам (нет сортировки по дате):
![alt text](/static/tags/image-16.png)
![alt text](/static/tags/image-17.png)
- поплыла верстка navbara на mozilla:
![alt text](/static/tags/image-18.png)
- сломанный поиск по тегам для не аккаунтов автора:
![alt text](/static/tags/image-19.png)
![alt text](/static/tags/image-20.png)

## Негативные кейсы
- ввод zalgo текста в названии тега:
![alt text](/static/tags/image-7.png)
- результат:
![alt text](/static/tags/image-8.png)
- попытка js-инъекции:
![alt text](/static/tags/image-9.png)
- результат (код не отработал):
![alt text](/static/tags/image-10.png)