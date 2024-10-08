## git checkout

git checkout [branch, file, tag or commit] [pathspec...]

<span style="color:#E9967A">**git checkout**</span> <span style="color:#008B8B">***[ветка, файл, тег или коммит] [путь...]</span>*** - переключение между ветками, отмена изменений в файлах до определенного коммита.

[**Здесь**](https://fig.io/manual/git/checkout "https://fig.io/manual/git/checkout") можно посмотреть обзор других параметров команды git checkout

<br/>


_Чтобы переключиться на главнкую ветку, используйте команду:_

```bash=
git checkout main
```

_Чтобы отменить изменения в файлах до определенного коммита, используйте команду:_

```bash=
git checkout -- <file>
```

![git-config](assets/git-checkout.png)

[_(Источник)_](https://snowsystem.net/git/git-command/git-checkout/)