Enquanto você estiver utilizando o Git através da linha de comando, provavelmente você também irá utilizar alguns comandos básicos no terminal enquanto passa pelo seu projeto e arquivos / pasta do sistema, incluindo:

pwd – que verifica onde você está no sistema de arquivos atual.
ls – lista arquivos no diretório atual.
cd [nome-do-diretório] – move-se para o nome ou caminho do diretório fornecido.
mkdir [nome-do-diretório] – cria um novo diretório com o nome escolhido.

#### Criando os repositórios
Quando você tem o desejo de utilizar o Git para um projeto, o primeiro comando que você deve executar é o git init, com o nome do seu projeto:

git init [nome do projeto]

Você irá executar este comando na linha de comando do Git Shell no diretório principal do seu projeto, o qual você poderá navegar no Shell utilizando os comandos que listamos acima.

Depois de executar esse comando o Git então criou um arquivo .git oculto dentro do diretório principal do seu projeto.

Este arquivo rastreia o histórico de versões do seu projeto e é o que transforma o projeto em um repositório Git, permitindo que você execute os comandos do Git nele.

#### Fazendo alterações

git add [arquivo] ou git add *

Depois de fazer as alterações em seus arquivos e escolher por capturá-los para o histórico de versões do seu projeto, você deve colocá-los na área de preparação com o git add, pelo nome do arquivo ou incluindo todos os arquivos na sua pasta atual utilizando o git add *.

git commit -m “[message]”

Para finalmente fazer o commit das alterações feitas nos seus arquivos da área de preparação para o histórico de versões do seu repositório, você precisa executar o git commit com uma mensagem descritiva de quais alterações foram realizadas.

git status

Se, a qualquer instante, você desejar visualizar um resumo dos arquivos que você modificou e ainda não confirmou, simplesmente execute o git status no repositório do seu projeto na linha de comando do Git Shel

#### Como funciona?

Agora, que temos os comandos básicos do Git no seu devido lugar, você pode utilizar o Git para capturar de forma instantânea o histórico de versões do seu projeto.

Basta que você inicialize um novo repositório executando o git init no diretório principal do seu projeto.

Usando git add * ou git add com os nomes dos arquivos específicos, você adiciona as suas alterações à área de preparação.

Finalmente, utilizando o git commit, você pode adicionar suas alterações ao histórico de versões do repositório.

A medida que você continua desenvolvendo o seu código, continue adicionando e confirmando suas alterações no seu repositório.