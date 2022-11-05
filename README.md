# LR6
**Лабораторная работа №6**

**Цель лабораторной работы:** изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием. 

**Порядок выполнения работы:**

**1.** Создать аккаунт на сайте GitHub

**2.** Сделать копию в личное хранилище из https://github.com/Kurtyanik/LR6/ (Fork).\
![0](https://github.com/1DIM2/LR6/blob/master/Screenshots/0.png)

**3.** Установить Git (https://git-scm.com/) \
![01](https://github.com/1DIM2/LR6/blob/master/Screenshots/01.png)

**4.** После установки настроить клиент git, введя имя пользователя и email.\
Настройка производится с использованием команд _git config --global user.name_ и _git config --global user.email_\
![1](https://github.com/1DIM2/LR6/blob/master/Screenshots/1.png)

**5.** Клонировать свой личный удалённый репозиторий на компьютер.\
Клонирование удаленного репозитория делается, используя команду _git clone_.\
![2](https://github.com/1DIM2/LR6/blob/master/Screenshots/2.png)

**6.** Добавить файл через интерфейс GitHub. Подтянуть изменения в локальный репозиторий.\
Для дальнейшей работы с файлами осуществляется переход в директорию LR6 командой _cd LR6_.\
![3](https://github.com/1DIM2/LR6/blob/master/Screenshots/3.png)

Подтягивание изменения из веб-интерфейса GitHub для клиента Git с помощью команды _git pull_.\
![4](https://github.com/1DIM2/LR6/blob/master/Screenshots/4.png)

**7.** Получить историю операций для каждой из веток.\
Просмотр истории операций ветки master, используя команду _git log_.\
![5](https://github.com/1DIM2/LR6/blob/master/Screenshots/5.png)

Просмотр задержания ветки в текущем репозитории команды _git branch_.\
![6](https://github.com/1DIM2/LR6/blob/master/Screenshots/6.png)

Переход в ветку branch1 командой _git checkout branch1_.\
![7](https://github.com/1DIM2/LR6/blob/master/Screenshots/7.png)

Просмотр коммитов ветки branch1 с помощью команды _git log_.\
![8](https://github.com/1DIM2/LR6/blob/master/Screenshots/8.png)

**8.** Просмотреть последние изменения.\
Просмотр последних изменений с помощью команды _git log -p_.\
![9](https://github.com/1DIM2/LR6/blob/master/Screenshots/9.png)

**9.** Выполнить слияние в ветку master, разрешив конфликт (можно использовать специальные редакторы или графический интерфейс git).\
Перед выполнением слияния необходимо вернуться в метку master с помощью команды _git checkout master_.\
![10](https://github.com/1DIM2/LR6/blob/master/Screenshots/10.png)

Выполнение слияния в ветке master, используя команду _git merge branch1_.\
![11](https://github.com/1DIM2/LR6/blob/master/Screenshots/11.png)

Так как файл mergefile.txt не отслеживается, используется команда _git status_ для отображения состояния рабочего каталога.\
![12](https://github.com/1DIM2/LR6/blob/master/Screenshots/12.png)

Добавление файла mergefile.txt с помощью команды _git add_.\
![13](https://github.com/1DIM2/LR6/blob/master/Screenshots/13.png)

Проверка отслеживания файла с помощью команды _git status_.\
![14](https://github.com/1DIM2/LR6/blob/master/Screenshots/14.png)

Конфликт разрешен, с помощью команды _git commit -m_ добавляется коммит со словом "Branches"\
![15](https://github.com/1DIM2/LR6/blob/master/Screenshots/15.png)

**10.** Удалить побочную ветку после успешного слияния.\
Удаление побочной ветки осуществляется при помощи команды _git branch -d_.\
![16](https://github.com/1DIM2/LR6/blob/master/Screenshots/16.png)

**11.** Сделать изменения и зафиксировать их, оставляя комментарии, несколько раз.\
Для создания комментариев в текстовом файле используется команда _echo "текст" > имя_файла.txt_. Текстом для первого комментария будет слово hello, название файла - change1.\
После создания файла применяется команда _git status_. Видно, что файл change1 не отслеживается. Нужно добавить его с помощью команды _git add_.\
Затем с помощью команды _git commit -m_ добавляется коммит.\
Аналогичным образом работа ведется с файлом change2.\
![17](https://github.com/1DIM2/LR6/blob/master/Screenshots/17.png)

Просмотр комментариев, используя команду _git log_.\
![18](https://github.com/1DIM2/LR6/blob/master/Screenshots/18.png)

**12.** Сделать откат коммита.\
Откат коммита осуществляется за счет команды _git reset --hard HEAD~1_.\
![19](https://github.com/1DIM2/LR6/blob/master/Screenshots/19.png)

**13.** Создать ветку для отчёта.\
Создание ветки для отчета и переход в эту ветку делается с помощью команд _git branch report_ и _git checkout report_.\
![20](https://github.com/1DIM2/LR6/blob/master/Screenshots/20.png)

**14.** Начать оформлять отчёт в файле README.md\
Это он.

**15.** Получить историю операций в форматированном виде (сокращённый хэш + дата + имя автора + комментарий). Добавить её в отчёт и сделать финальную фиксацию изменений.\
![21](https://github.com/1DIM2/LR6/blob/master/Screenshots/21.png)

**16.** Отправить локальные изменения в сетевое хранилище GitHub.\
Отправка изменений осуществляется командой _git push_.\
![22](https://github.com/1DIM2/LR6/blob/master/Screenshots/22.png)
