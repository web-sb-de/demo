# 1. Setup

## 1.1. Github / Terminal

- Neues Git Repo erstellen

```bash
cd ~/Documents/software/
NAME=ffw-web-sb-de;
gh repo create $NAME --private &&
git clone https://github.com/sbbrnnr123/web-sb-demo.git $NAME &&
cd $NAME &&
git remote set-url origin https://github.com/sbbrnnr123/$NAME.git &&
git push -u origin main
```

## 1.2. Custom domain

- DNS A, AAAA und CNAME Einträge auf Github Pages
- Github Pages einrichten (./public, SSH, apex/subdomain)

## 1.3. Hugo Projekt

- hugo.json
- footer.html
- impressum.html
- /content befüllen
- /content Bilder in webp umwandeln
- ./build.sh
