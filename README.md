# Default System

Este projeto serve para prover a estrutura básica de um sistema Java com Spring Boot.

### Configuações

#### Acesso ao H2
Acesso pelo link: ```http://localhost:8080/h2-console``` <br />
Obs.: O JDBC URL deve estar igual a "jdbc:h2:mem:testdb".


### Como fazer a copia deste projeto em um novo repositório?

#### Step 1 - Abrir o terminal de acesso ao GIT

#### Step 2 - Criar um "bare" clone a partir do repositório
```git clone --bare https://github.com/nt-noobs/default-system.git```

#### Step 3 - Acesse o repositório clonado.
```cd default-system.git```

#### Step 4 - Agora no GITHUB, crie um novo resitório clicando no botão "New" em "https://github.com/nt-noobs"
Coloque um nome que faça sentido para o seu projeto. Exemplo: meu-projeto-example. </ul>

#### Step 5 - Crie o espelho enviando o projeto clonado para o github
```git push --mirror https://github.com/nt-noobs/meu-projeto-example.git```

#### Step 6 - Limpar a sujeira
```cd ..```
```rm -rf default-system.git```

#### Step 7 - Clone do Projeto
```git clone https://github.com/nt-noobs/meu-projeto-example.git```

#### Step 8 - Alteração do POM.xml
Alterar a tag "nome" e "artifactId" para o nome do novo projeto.
Também alterar qualquer referência ao nome default-system ou defaultsystem, pelo novo nome do projeto.

#### Step 9 - Abrir o projeto na IDE desejada.

<br />
### Cada exercício deve ser enviado em um branch separado, como fazer?

#### Step 1 - Criar um branch a partir da master (o nome tem que fazer sentido)
```git checkout -b my-branch```

#### Step 2 - Adicionar no repositório local
```git add .``` 

#### Step 3 - Desenvolver o exercício e commitar
```git commit -m '[exercício 1] Descrição do exercício'``` 

#### Step 4 - Enviar
```git push origin my-branch``` 

#### Step 5 - Voltar para a master
```git checkout master``` 

#### Step 6 - Merge com o branch
```git merge my-branch``` 

#### Step 7 - Envia atualização da master para o repositório origin
```git commit -m '[exercício 1] Descrição do exercício'``` 

#### Step 8 - Enviar
```git push origin master```
