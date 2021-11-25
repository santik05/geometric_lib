# “Отчет о проделанной работе”
### “Автор: Салимов А.З.”
[Ссылка на репозиторий с уроком про животных](https://github.com/santik05/origin)

#### “Ход работы”

* git clone https://github.com/smartiqaorg/geometric_lib
* git checkout feature
* git checkout develop
* git log --graph --all
* git checkout main
* git merge develop --no-ff
* git reset --hard HEAD^
* git merge develop --ff
* git checkout release
* git rebase -i main
* git checkout --their docs/README.md
* git add -A
* git rebase --continue
* git checkout main
* git merge release --ff
* git push --all git@github.com:santik05/geometric_lib.git
