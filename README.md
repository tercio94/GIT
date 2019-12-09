# Guia prático GIT

1. Instalando o GIT no computador:
[GIT](https://gitforwindows.org)

2. Depois de instalado basta criar qualquer pasta e clicar com o botão direito do mouse para abrir o Prompt que irá executar
os comandos do GIT:

<img src="https://user-images.githubusercontent.com/54813775/70244725-bf740e80-1753-11ea-86a5-7ec0ff5c43da.png"
height="400" width="400">

3. Para criar um novo repositório basta digitar:
```
git init
```
dentro do prompt de comando.

<img src="https://user-images.githubusercontent.com/54813775/70246078-e5021780-1755-11ea-8d91-9a4d56b083e2.png"
height="400" width="400">

4. Adicionando arquivos dentro do seu projeto e commitando.

adiciona todos arquivos que tem na pasta.
```
git add .
```
adiciona um arquivo específico. 
```
git add nome do arquivo
```

<img src="https://user-images.githubusercontent.com/54813775/70449644-14c85c80-1a81-11ea-8884-86da2f752df0.png"
height="400" width="400">

commitando os arquivos que foram adicionados.
```
git commit -m "escreva algo"
```

<img src="https://user-images.githubusercontent.com/54813775/70450009-bcde2580-1a81-11ea-9651-9aa1e7a15bce.png"
height="400" width="400">

5. Enviando alterações para o repositório remoto:

Suas alterações agora estão no HEAD da sua cópia de trabalho local. Para enviar estas alterações ao seu repositório remoto, execute:
```
git push origin master
```
Se você não clonou um repositório existente e quer conectar seu repositório a um servidor remoto, você deve executar:
```
git remote add origin link_do_github ou servidor remoto
```
Altere master para qualquer branch desejado, enviando suas alterações para ele. Para criar uma nova branch basta executar:
```
git branch nome_da_nova_branch
```
Mudar para a nova branch que foi criada:
```
git checkout nome_da_nova_branch
```
Voltar para o master:
```
git checkout master
```
Commitando alterações que foram feitas apenas dentro da nova branch:
```
git push origin nome_da_nova_branch
```

<img src="https://github.com/tercio94/git/blob/Testando/git/branchnova.png?raw=true"
height="400" width="400">















