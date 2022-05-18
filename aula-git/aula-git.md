## Aula sobre git

### Criar um novo repositório local (pc)
- Dentro da pasta, abra um terminal e execute o comando

```shell
git init
```
- Este comando inicializa um repositório local na pasta do projeto.

Após criar remotamente, conecte com o repositório remoto
- criar o repositório no GitHub
- seguir os próximos passos

```shell
  echo "# teste" >> README.md
  git init
  git add README.md
  git commit -m "first commit"
  git branch -M main
  git remote add origin git@github.com:martadrozsa/teste.git
  git push -u origin main 
```
ou envie um repositório existente a partir da linha de comando
```shell
git remote add origin git@github.com:martadrozsa/teste.git
git branch -M main
git push -u origin main
```
___________________________________

### Verificar status dos arquivos

```shell
git status
```
___________________________________

### Adicionar um arquivo em específico
```shell
git add <exemplo.md>
```
### Adicionar todos os arquivos ao repositório

```shell
git add *
```
___________________________________

### Comitar

#### Comitar informando uma mensagem
```shell
git commit -m "Firts commit"
```
___________________________________

### Enviar arquivos para o repositório remoto
```shell
git push
```

___________________________________

### Atualizar os arquivos em nosso repositório local em relação aos do repositório remoto
```shell
git pull
```
___________________________________

### Clonar arquivos de um repositório remoto
- abrir um terminal local na pasta que queremos clonar o projeto
- copiar a URL do repositório remoto
- digitar o comando 
```shell
git clone <git@github.com:martadrozsa/it-bootcamp-meli-exercicios.git>
```
- pressionar enter
