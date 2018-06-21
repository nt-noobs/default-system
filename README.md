# default-system

Este projeto serve com prover a estrutura básica de um sistema.

<h2>Configuações</h2>

<ul> Acesso ao H2</ul>
http://localhost:8080/h2-console
    -> JDBC URL: jdbc:h2:mem:testdb

<h2>Copia deste projeto em um novo repositório</h2>

### <ul>Step 1 - Abrir o terminal de acesso ao GIT.</ul>
### <ul>Step 2 - Criar um "bare" clone a partir do repositório.</ul>
git clone --bare https://github.com/nt-noobs/default-system.git
### <ul>Step 3 - Acesse o repositório clonado.</ul>
default-system.git
### <ul>Step 4 - Agora no GITHUB, crie um novo resitório clicando no botão "New" em "https://github.com/nt-noobs". 
Coloque um nome que faça sentido para o seu projeto. Exemplo: meu-projeto-example. </ul>
### <ul>Step 5 - Crie o espelho enviando o projeto clonado para o github.</ul>
git push --mirror https://github.com/nt-noobs/meu-projeto-example.git
### <ul>Step 6 - Limpar a sujeira.</ul>
cd ..<br/>
rm -rf default-system.git
### <ul>Step 7 - Clone do Projeto.</ul>
git clone https://github.com/nt-noobs/meu-projeto-example.git
### <ul>Step 8 - Alteração do POM.xml.</ul>
Alterar a tag nome e artifactId para o nome do novo projeto.
### <ul>Step 9 - Abrir o projeto na IDE desejada.</ul>


<h2>Cada exercício deve ser enviado em um branch separado, como fazer</h2>

### <ul>Step 1 - Criar um branch a partir da master (o nome tem que fazer sentido)</ul>
git checkout -b my-branch

### <ul>Step 2 - Adicionar no repositório local</ul>
git add .

### <ul>Step 3 - Desenvolver o exercício e commitar</ul>
git commit -m '[exercício 1] Descrição do exercício'

### <ul>Step 4 - Enviar</ul>
git push origin my-branch

### <ul>Step 5 - Voltar para a master</ul>
git checkout master

### <ul>Step 6 - Merge com o branch</ul>
git merge my-branch

### <ul>Step 7 - Envia atualização da master para o repo</ul>
git commit -m '[exercício 1] Descrição do exercício'

### <ul>Step 8 - Enviar</ul>
git push origin master
