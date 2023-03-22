# -7DaysOfCode-GitHub
#7DaysOfCode - GitHub  (desafio alura)

GitHub 1/7: 👩🏽‍💻 Criando um repositório
O repositório foi criado manualmente pelo proprio site do git e add o readme

GitHub 2/7: 👩🏽‍💻 Adicionando um projeto ao repositório
Foi realizado uma pagina fake simples apenas para conter itens para enviar para o repositório, para isso foi iniciado o git no pc e conectado no repositorio criado usando os seguintes comandos para realizar a configuração e o envio dos arquivos.

git init
git status
git add .
git commit -m "mensagem do commit"
git branch -M main
git remote add origin <link_para_o_seu_repositorio>
git push -u origin main

GitHub 3/7: 👩🏽‍💻 Clonando um repositório
Criar uma pasta no pc e digitar o seguinte comando
git clone <link_para_o_seu_repositorio>

GitHub 4/7: 👩🏽‍💻 Realizando um commit a partir do VSCode
![image](https://user-images.githubusercontent.com/83456621/226773359-c6706163-ec73-4ae6-8cd6-0401626895ed.png)
Para realizar o push
![image](https://user-images.githubusercontent.com/83456621/226773448-ae46d0e7-9764-46aa-9ca3-90551549f914.png)

GitHub 5/7: 👩🏽‍💻 Revertendo um commit
Na pasta do repositório abrir o terminal e digitar o seguinte comando
git revert HEAD~1

GitHub 6/7: 👩🏽‍💻 Resolvendo um conflito
git checkout <nome do branch com conflito>
git pull origin main
abra o arquivo com conflito e os resolva
salve o arquivo
git add <nome do arquivo alterado>
git commit
git push -u origin main

GitHub 7/7: 👩🏽‍💻 Fazendo o deploy no GitHub Pages
![image](https://user-images.githubusercontent.com/83456621/226774491-4e85cb7c-cf07-4a8e-8b36-7c92e70a559a.png)
![image](https://user-images.githubusercontent.com/83456621/226774543-cf103681-2c4b-4883-a956-41abdabb632c.png)
Salvar e para acessar basta digitar o nome do usuario . github.io / nome do repositório
https://marina-gajego.github.io/-7DaysOfCode-GitHub/
