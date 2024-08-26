# git_101

# Workshop Git, GitHub, Gitlab

[Github]()
[GitLab]()

---

> Git
> Github
> GitLab

- Git: Versiyon kontrol sistemi
- Github: Git Repository

## Git Config

```sh
git -v
git --version
git help
git config --global user.name
git config --global user.name "Kübra Ağdaş"
git config --global user.email
git config --global user.email "kubraagdass@gmail.com"
git config --global core.editor "notepad++"
git config --global -l
git config core.autocrlf true
```

---

## Git Sıklıkla Kullanılan Komutlar

```sh
clear
git status
git log
```

---

## Git Remote

```sh
git init
git add .
git add dosyaAdi1 dosyaAdi2
git commit -m "initial commit"
git remote add origin gitHubURL
git remote
git branch -M main
git push -u origin
```

---

## Git Commit

```sh
git add .
git commit -m "mesaj adını"
git push
NOT: Eğer önceden ilgili dosya "git add" ile eklenmişse
git commit -a -m "commit adı"
git push
```

---

## Git Hakkında

```sh
Git Nedir ?
- Global Information Tracked kısaltmasıdır
- VCS version Control System
- Repository: Github, GitLab vs
- En önemli özelliği: Dağıtık olması. Aynı anda birden fazla kişiyle çalışabiliriz.
- Ücretsiz
- Açık kaynak kodludur.
- Git yazarı Linux çekirdeğini yazan Torvalds 2005 yılında yazıyorlar
- Eski kodlarımıza erişim sağlıyabiliyoruz.
- Dosya değişikliğini önceki sürümlere geçerek sağlayabiliyoruz.
```

---

## Git Clone

```sh
git clone https://github.com/hamitmizrak/Workshop_Git_GitHub_GitLab.git
```

---

## Git Alias

```sh
git log --decorate --oneline --graph --all
git config --global alias.graph "log --decorate --oneline --graph --all"
git graph
```

---

## Git Remote

```sh
git remote
git remote set-url yeniRemoteAdi URLYazıyoruz
```

---

## Git Diff

```sh
git log
git diff commitID1 commitID2
git diff  dad5338a1bc2109e93dc89b26dbab5f75485f521 fe795f46ba672
```

---

## .gitignore

```sh
#Bu dosyayı takip etme
secret.txt

#React, Angular vs
node_modules
```

---

## Git Stash

```sh
git add .
git stash
git stash save "stash kendi ismi"
git stash list

git stash apply stash:{0}
git stash drop stash:{0}

git stash pop
```

---

## Git Tag

```sh
git add .
git tag v1.0.0
git show v1.0.0
git checkout v1.0.0
git checkout v1.0.0
git push origin v1.0.0
git tag --delete v1.0.0
```

---

## Git Pull/Fetch

```sh
git pull: uzak repodaki bütün dosyaları hemen local pojemize ekler. Genelde conflict yeriz.

git pull
git pull origin

git fetch: biz kontrol ettikten sonra istersek local projemize ekleriz.
Not: Conflict yememek için kullanmak gerekir.

git fetch
git branch -a
git checkout remotes/origin/main
git checkout main
git merge origin/main
```

---

## Git Branch

```sh

```

---
