grupo quando forem adicionar no main escrevam esse comando antes do push: git pull --rebase origin main

passo a passo no terminal:

git init

git add .

git commit -m "adicionando arquivo: <seu nome>"
  
git branch -M main
  
git remote add origin https://github.com/scrum-tds/repositorio-compartilhado.git
  
### git pull --rebase origin main
  
git push -u origin main

