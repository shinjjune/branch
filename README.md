## git class 20190829


## git 특강(2019_08_29)

#### git을 통한 협업하기 (push/pull)

- git bash

```
mkdir codes
cd codes

code .
```

VScode

github -> repository ->settings ->collaborators

- codes/README.md



```
# 끝말잇기
git을 통한 협업 프로젝트

## 협업시작
부하는 들어라. 끝말잇기 시작해라.
```

- git bash

```
git init
git status

git add readme.md
git commit -m "first commit" (m : messeage)
git log
git log --oneline
```

대장은 협업 repository 만든다

git remote add origin https://github.com/JHscar/ggutmalpjt.git

git push - u origin master





#### <부하>

```
mkdir buha

cd buha
```

clone을 통해 코드를 가져온다.

```
git clone https://github.com/JHscar/ggutmalpjt.git
code .

git pull origin master

git add README.md

git commit -m "blabla"

git push origin master
```



#### <대장>

```
git pull origin master

git add README.md

git commit -m "blabla"

git push origin master
```





### fork

내가 수정해서 제안해볼게

내거를 수정해서 pull-request

create pull request



### git branch

->  실전에서 하게될 협업 flow

branching

```
mkdir branch
cd branch

VSCODE
branch/index.html
```



##### emmet

checkout #hash



git merge side

git checkout -b member

branch 지우는 법

git branch -d side
