# Шпаргалка по GitHub Classroom

В данном мануале приблизительно постараюсь описать работу в данном сервисе. Вашей задачей является понять, разобраться самостоятельно, куда да как тыкать.

Кратко говоря, платформа нужна для того, чтобы вы, ученики, загружали свой код, а преподаватель его проверял и давал фидбэк по вашему коду. GitHub Classroom даёт все возможности для этого.

# Создание репозитория (репозиторий = проект. В вашем случае, проект = задача)

 Всё начинается с этого. Преподаватель отправляет вам ссылку на какую-то задачу. Заходя по нему, система автоматически создаёт готовый репозиторий, где в файле README.md будет написана постановка задачи, а также в проекте могут быть и иные готовые файлы. В общем, всё, что вам нужно для решения.
 
 ## Работа с репозиторием
 
 После создания репозитория, встаёт вопрос, как с ним работать, как его редактировать, вносить новые файлы и пр. Для этого, вы крайне желательно должны работать с репозиторием локально. Значит, склонировать репозиторий к себе на ПК из облака (Github'а)(На данном этапе крайне рекомендую скачать GitHub Desktop и разобраться с тем, как с ним работать: создать туториальный репозиторий и поиграться).
 ![image](https://user-images.githubusercontent.com/113031927/215781050-47f1ef63-5b81-434a-84c1-e748908b2ebe.png)


Далее, после клонирования репозитория вы можете вносить изменения в локальный репозиторий независимо от облачного. Ваш репозиторий будет находиться в одноимённой папке. Можете добавлять файлы, редактировать и пр.

**Примечание: редактируем только ветку main. Не создаём иные ветки и пр. Вы работаете только в ветке main, не трогайте ветку feedback.**

## Внесение изменений в силу

После того, как вы внесли изменения в код, нужно сделать так называемый коммит - снимок проекта, сохранение. Данная операция сохранит текущее состояние кода. Воспринимайте сохранения как в играх. Вы можете в любой момент вернуться к конкретному коммиту.
![image](https://user-images.githubusercontent.com/113031927/215781514-82901146-a487-4563-9a26-4359177fb0ee.png)


После коммита, вы можете синхронизировать в одностороннем порядке ваш локальный репозиторий с репозиторием в GitHub. Для этого вы делаете операцию Push. А для того, чтобы вытянуть обновления с облачного репозитория, вы делаете операцию Pull
![image](https://user-images.githubusercontent.com/113031927/215781707-7fcfe039-3530-4adf-a2d5-e2090f23bf06.png)



## Pull Request

После того, как вы сделали операцию Push, GitHub Classroom автоматически обновит Pull Request. PR требуется для того, чтобы преподователь мог дать оценку вашему коду, подметить ваши ошибки и пр. Следите за Pull Request'ом. Если код утверждён, то всё хорошо. Иначе, вы увидите оставленные комментарии по поводу ваших ошибок и пр.
![image](https://user-images.githubusercontent.com/113031927/215782072-56e0919d-fc3f-4884-8db6-e02cd4cf7c5b.png)

