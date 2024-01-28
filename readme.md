====================управление bash===================
- pwd - узнать в какой папке ты находишься
- cd (адрес) - сменить директорию (
 cd ~ - домой
 cd .. - перейти на папку ВЫШЕ
 )
- ls - отобразить содержимое директории (ls -a - отобразить со скрытыми файлами)
- touch (название . расширение) - создать файл(touch имя . расширение)
- mkdir (название)- создать папку(
mkdir -p a/b/c/d... - создать несколько папок друг в друге с помощью флага -p
)
- cp (что копируем куда копируем) - копировать 
- mv - перенести файл (mv что копируем куда копируем)
- cat (название) - прочитать файл(только txt) 
- rm (название файла) - удалить файл
- rmdir (название папки) - удалить папку (если в ней есть файлы, то тебя предупредят "Directory not empty")
- rm -r (название) - удалить несмотря на файлы в папке 
- git config --global user.name "User Namovich" - написать свой никнейм
- git config --global user.email username@yandex.ru - написать email
- cat ~/.gitconfig - узнать имя, email
=========================Git=======================
- git init - создаем репозиторий
- rm -rf .git - удалили репозиторий .git
- git status - узнать текущее состояние репозитория
- git add (--all) - отслеживать файл в репозитории (un/tracked) 
- git add - при повторном введении, подготавливает к сохранению
- git commit -m 'Мой первый коммит!' - сохраняем файлы. Только после подготовки (ADD -all) 
- git log - посмотреть историю коммитов
- ls -la .ssh/ - вывели список созданных ключей ssh
- ssh-keygen -t ed25519 -C "электронная почта" - генерируем ssh связку ключей
- git remote add "origin" "URL" - связываем удаленный репозиторий с локальным. Даем 2 аргумента "origin" - название (стандартный псевдоним), URL - копируем на GitHub
- git remote -v - убедиться, что онлайн и оффлайн репозитории связаны
- git push - выгрузить в онлайн
git push -u origin main/master - в первый раз
-u - свяжет локальную ветку с одноимённой удалённой
origin - 
- привет