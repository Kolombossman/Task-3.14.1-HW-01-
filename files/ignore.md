[< к содержанию](/README.md)

## .gitignore

.gitignore 

<span style="color:#E9967A">**.gitignore**</span> <span style="color:#008B8B">***</span>*** - файл создается для указания файлов и каталогов, которые на будет остлеживаться  Git.


<br/>


_Чтобы Git игнорировал ненужные файлы, нужно создать файл .gitignore и добавить в этот файл следующие праила:_

```bash=
# Игнорирование временных файлов
*.log
*.tmp

# Игнорирование конфигуравционных файлов 
*.config

# Игнорирование всех файлов внутри директории
/assets/*
/bin/*
/obj/*

# Игнорирование файлов с расширениями
*.pdb
*.exe

```
