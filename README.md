## GIT useful commands
New Local Branch:
> git checkout -b "branch\_name"

Delete Local Branch:
> git checkout master

> git branch -D branch\_name

Push New Branch:
> git push origin branch_name

Delete Remote Branch:
> git push <remote_branch> --delete <branch_name>

Dejar de trackear archivos ya trackeados por git (.gitignore no los toma cuando sucede esto):
> git update-index --assume-unchanged ruta_al_archivo/nombre_del_archivo

Volver a trackear archivos destrackeados
> git update-index --no-assume-unchanged ruta_al_archivo/nombre_del_archivo

Deshacer cambios locales NO staged
> git checkout -- file\_name

Deshcaer cambios locales staged
> git reset HEAD file\_name

> git checkout -- file\_name
