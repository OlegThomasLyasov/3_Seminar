# Мой проект

## Какое настроение у вас?
* веселое :smiley:
* грустное :unamused:
* дружелюбный :sweat_smile:
* рабочее
* осеннее
* спортивное
* отличное 
* боевое :angry:

# Работа с удаленными репозиториями

### Основные команды для работы с удаленными репозиториями:

* git clone

Копировать внешний репозиторий на свой ПК можно командой **git clone**.

*Команда **git clone** составная: она не только
загружает все изменения, но и пытается слить 
все ветки на локальном компьютере и в
удаленном репозитории*.

Например, чтобы загрузить репозитарий находящийся по адресу: https://github.com/OlegThomasLyasov/3_Seminar, необходимо выполнить команду **git clone** https://github.com/OlegThomasLyasov/3_Seminar.

* git pull

*Эта команда позволяет (подтянуть) скачать все 
из текущего внешнего репозитория и автоматически
сделать merge с нашей версией*.

* git push

*Эта команда позволяет отправить нашу
версию репозитория на внешний
репозиторий*. 

# Важно!
```
При первом использовании команды git push нужна авторизация на внешнем репозитории.
```

## Для чего нужен **pull request**?

***pull request** — это запрос на вливание изменений в какой-то репозиторий*.

То есть, это запрос, который позволит другим людям предлагать
изменения в наш проект.

## Как сделать **pull request**?

1. Делаем **fork** внешнего репозитария на сайте Github
2. Делаем **clone СВОЕЙ** версии репозитария
3. Создаем новую ветку и в **НЕЕ** вносим свои изменения
4. Фиксируем изменения (**делаем коммиты**)
5. Отправляем **СВОЮ** версию в **СВОЙ Github**
6. На сайте Github нажимаем кнопку **pull request**  
