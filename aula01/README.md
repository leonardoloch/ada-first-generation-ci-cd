# AULA 01


### Comandos
Mudar para um branch e ja criar.
```bash
git checkout -b nodeDaBranch
```


Adicionar todos os arquivos para sua area de staging 
```bash
git add . 
```
Enviar o código para o seu repotório local
```bash
git commit -m "adicine uma mensagem aqui"
```

Enviar o código para o seu repotório remoto
```bash
git push
```
Se for a primeira vez que esta fazendo um push deve criar um repositório remote
```bash
git push --set-upstream origin nodeDaBranch
```
Para atulizar o repositório local com as alterações do repositório remoto
```bash
git pull
```

Para ver as mudaças locais
```bash
git status
```
Para comparar duas branchs
```bash
git diff branchA branchB
```
