# Template DDD e sua missão

Criar rapidamente o escopo de uma arquitetura DDD ou servir de consulta.
# Como utilizar?
1° Clone o projeto:
```
git clone https://github.com/IamHerica/template-ddd.git
```
***
2° Dentro de uma pasta, instale o template:
```
dotnet new --install C:\Users\heric\Desktop\Estudos
```
Eu por exemplo, clonei o repo dentro da pasta Estudos, e por isso, ao fazer a instalação eu apontei a pasta onde contém meu arquivo.
***
3° Verificar se o template está disponivel:
```
dotnet new --list
```

O template deverá aparecer lá, dessa maneira:
```
DDD Template                                     dddtemplate          [C#]        Console
```
É possível utilizar o dotnet new dddtemplate --help para ver quais flags o template permite passar.
***

4° Utilizar o template sem dó e piedade

```
dotnet new dddtemplate -o teste -n nome
O modelo "DDD Template" foi criado com êxito.
```

*** 
# Observações:
Dentro de cada pasta possui um .gitignore, que foi colocado apenas com a intenção de subir as pastas no GitHub, já que sem algum arquivo dentro não seria possível.

Curso que aprendi DDD e muito mais: https://www.udemy.com/course/clean-architecture-essencial-asp-net-core-com-c/
