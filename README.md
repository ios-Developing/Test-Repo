Git instruction

# start homework for lesson 2

*Шрифт курсив*

**Шрифт жирный**

~~Зачеркнутый шрифт~~

# Заголовок 1

## Заголовок 2

### Заголовок 3

Пошли списки:
 Здесь будут созданы списки, они будут создаваться в новой ветке.
 * Раз
* Два
    * Два-1
    * Два-2
* Три
 1. Один
 2. Второй
 3. Второй 

Новые изменения в ветке Lists
 
продолжаем редактировать файл в ветке Лист. 2 commit !!!

сделали ветку list2 из ветки list! и конечно закоммитим!

#Инициализация git
    git init 

#Узнаем версию git 
    git --version

#Установим имя для пользователя  
    git config --global user.name "<имя>"

#Теперь установим email
    git config --global user.email "<адрес@email.com>"

#Добавим все файлы проекта в нам будующий commit
    git add .
#Или так
    git add --all

#Если хотим добавить конкретный файл то можно так
    git add <имя_файла> 

#Теперь создаем commit. Обязательно указываем комментарий. И не забываем про кавычки
    git commit -m "<комментарий>"

#Показать всю историю коммитов начиная с последних
    git log

#Переключение в HEAD ветки
    git checkout <ветка>

#Скачать изменения и сразу слить/интегрировать их в HEAD
    git pull <репо> <ветка>
    
#Опубликовать локальные изменения в удаленном репозитории
    git push <репо> <ветка>

checkout

