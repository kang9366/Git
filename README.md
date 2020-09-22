# How to use git?

#### 이름, 이메일 config
```
git config --global user.name "name"
git config --global user.email "email"
```

#### 디렉토리 변경
```
cd "path"
```

#### 현재 디렉토리에 있는 파일 및 폴더 확인
```
ls
```

#### local repository 생성
```
git init
```

#### 원격 repository 내려받기
```
git clone "repository address"
```

#### remote repository 추가
```
git remote add "remote repository name" "git hub repository address"
```

#### remote repository 이름 변경
```
git remote rename "old name" "new name"
```

#### remote repository 삭제
```
git remote rm "repository name"
```

#### 현재 생성된 remote repository 확인
```
git remote
```

#### commit 추가
```
git commit -m "message"
```

#### 현재 상태 확인
```
git status
```

#### 파일 or 폴더 삭제
```
git rm -r  --cached "file name"
```
#### push
```
git push "remote repository name" master
```

#### pull
```
git pull "remote repository name" master
```

#### commit 리스트 확인
```
git log
```
