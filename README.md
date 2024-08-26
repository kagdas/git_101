# git_101

# Workshop Git, GitHub, Gitlab

[Github]()
[Github]()

---

## Git Version

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

## Git

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

## Git Sıklıkla Kullanılan Komutlar

```sh
clear
git status
git log
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
