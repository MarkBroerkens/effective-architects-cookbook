# git

* Git Flight Rules - use case based Git tutorial - [https://github.com/k88hudson/git-flight-rules](https://github.com/k88hudson/git-flight-rules) 

create a new repository then duplicate your code from last project to it.

```bash
git clone --bare https://github.com/exampleuser/old-repository.git

cd old-repository.git
git push --mirror https://github.com/exampleuser/new-repository.git

cd ..
rm -rf old-repository.git
```

Source: [https://help.github.com/articles/duplicating-a-repository/](https://help.github.com/articles/duplicating-a-repository/)

