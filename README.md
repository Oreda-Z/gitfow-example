GitFlow
1. Создать репозиторий на GitHub и клонировать его на компьютер.
2. Создать файл .gitignore и добавить .idea/
3. Создать ветку разработки develop от главноей ветки (master, main) git checkout -b develop и отпрваить её на GitHub.
4. Создать от ветки develop feature/-ветки и мержить feature/-ветки в develop, когда фичи будут выполнены.
5. Слияние веток через GitHub (pull request).
6. git pull origin develop.
7. Создание ветки release/0.1.0 от develop, в эту ветку добавлять фичи уже нельзя, только правка багов.
8. Когда ветка release/0.1.0 закончена то она мержится в develop и main и затем удаляется.