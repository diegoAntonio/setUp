### SetUp
----
Template para inicio r�pido do desenvolvimento
de projetos.

#### Instala��o
----
1. Clonar reposit�rio:
```
$[localhost git] git clone git@github.com:diegoAntonio/setUp.git
```
2. Renomear a pasta do projeto
```
$[localhost git] mv setUp Nome_Projeto
```
3. Entrar na pasta e trocar a branch conveniente (lista de branchs abaixo)
```
$[localhost <Nome_Projeto>] git checkout Nome_Branch 
```
4. Fazer merge com a master
```
$[localhost <Nome_Projeto>] git merge master 
```
5. Eliminar as outras branches
```
$[localhost <Nome_Projeto>] git branch -D Nome_Branch 
```
6. Alterar a referencia do origin 
```
$[localhost <Nome_Projeto>] git remote add origin git@github.com:diegoAntonio/setUp.git
```
7. Subir modifica��es
```
$[localhost <Nome_Projeto>] git push -u origin master
```
8. Criar arquivos de configura��o da IDE Eclipse:
```
$[localhost <Nome_Projeto>] ./gradlew eclipse
```
9. Importar o projeto para a IDE Eclipse
```
   File -> Import Project
```

#### Branches

Ainda em desenvolvimento