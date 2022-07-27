#задать имя и эмейл 
git config --global user.name "Your name" 
git config --global user.email "user@mail.ru"

git config --global http.sslVerify false                # отключить проверку сертификата
git update-git-for-windows                              #обновить гит до последней версии


git --version                                           #запрос версии гита 

PS G:\py\git_for_GB> git init                           #эта папка будет отслеживаться git-ом 

git status                                              #показыввете статус работы папки под контролем версий
                                                        
ltcm vj;tn ,nm rjyak                                                        
                                                        #Untracked files: - это не отслеживаемые файлы (красным цветом)
                                                        #Зеленым отслеживаемые файлы

git add '.\hello wirld.md'                              #отслеживает файл '.\hello wirld.md'
git commit -m "Создали новый файл"                      #Сохранение изменений, Коментирование событий
git commit --amend -m 'new row in New32'                #перееминовать последний комит

git log --oneline                                       #все события
git log --graph                                         #все события c визуализацией веток
   

git branch                                              #Посмотреть ветки
git branch [text_formatting]                            #создать ветку text_formatting
git branch -d [text_formatting]                         #удалить ветку text_formatting

git checkout [comit:b287]                               #переключаться между версиями
git checkout 'master'                                   #переключение на ветку master

git merge [text_formatting]                             #объеденить текущую ветку с text_formatting

git diff                                                #показывает какие изменения совершенны с файлом

git branch -m newBranchName                             # переименовать текущую ветку
