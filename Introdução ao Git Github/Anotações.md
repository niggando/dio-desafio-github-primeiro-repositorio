# Anotações sobre GIT/GITHUB

## Comandos Básicos:

### Configurando

#### git config --global user.name "Seu Nome"
Definindo meu usuario.
#### git config --global user.email seuemail@gmail.com 
Definindo o email, de preferência, o mesmo utilizado no GitHub para que as commits tenham o mesmo nome.

### Criando o projeto

#### git init
Este comando cria um novo repositorio oculto dentro da pasta em que utilizou o mesmo, contendo todos os arquivos necessários para a criação de um repositório (esqueleto de repositório Git).
    Dica: utilizar o _GitBash here_ agiliza bastante a navegação dentro do console, uma vez que já te coloca na pasta desejada.

#### git clone
Este comando clona algum repositório dentro do diretório desejado e possui três formas de entrada diferentes, sendo elas: 
 - HTTPS -> simples de usar e solicita autenticação através de uma janela pop-up de loguin.
 - SSH -> utilizada durante o curso após uma breve verificação de autenticidade.
 - GitHub CLI -> Ainda não utilizei, será meu próximo teste.

    _Além destas formas, há como baixar o repositório de alguém através do aplicativo Desktop do GitHub e através de um arquivo ZIP._

### Monitorando Novos Arquivos
Inicialmente, os arquivos monitorados encontram-se inalterados. Conforme edições são feitas nos arquivos do repositório, seja este clonado ou criado, o Git passa a interpretá-los como modificados justamente por terem sido feitas edições desde o último commit. Você seleciona os arquivos modificados e realiza um novo commit das alterações, tornando-o o mais atual e novamente inalterado. Eis que o ciclo se repete. 
    Os comandos a seguir fazem parte do ciclo básico de monitoramento.

#### git add
O comando _git add_ é utilizado quando você deseja passar a monitorar um novo arquivo.

#### git status
Este comando verifica os arquivos de determinado repositório, verificando se há arquivos novos e qual a situação atual dos arquivos existentes.

### git commit
Este comando armazena o conteúdo atual (monitorado) em um novo commit, chegando à sua última fase: _stage_. O ato de "commitar" é dizer que o repositório em sua máquina está pronto para ser "empurrado" como o arquivo mais atual, além de conter uma mensagem descrevendo as mudanças.

### git push
Este comando significa "empurrar" e, de fato, você empurra os arquivos alterados localmente para o repositório remoto, contendo todos os commits e seus comentários oriundos das alterações.

## Links úteis

[Link para download do Git](https://git-scm.com/)

[Lista de comandos do git - completa](https://comandosgit.github.io/)

### Recado para o futuro: Isso é só o começo! Obrigado por ler!
