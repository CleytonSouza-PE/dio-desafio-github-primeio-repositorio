Passo a passo do cliclo de vida


GIT INIT
Esse comando inicializa o conceito do git chamado repositório. Quando usamos esse comando estamos iniciando um repositório do git dentro da referida pasta.

Trackend ou Untracked.

Trancked
Dentro de Tranked ficam os arquivos realmente rastreados pelo git ou seja, os arquivos que o git tem ciência deles, podendo se dividir em três estágios diferentes: Unmodified, Modified e Staged.

Unmodified
São os aquivos que ainda não foram modificados.

Modified
São os arquivos Unmodified que receberam modificações e são mudados automaticamente de Unmodified para Modified.

Stagend
São os aquivos que estão preparados para fazer parte de um commit.


Untracked
Untracked são os arquivos que o Git não tem ciência deles.

Commit: 
O commit retorna todos os arquivos para Unmodified para recomeçar o ciclo, ele representa o estado final daqueles arquivos, é feita a junção de todos aqueles arquivos salvando todos criando um snap shot como se tirasse uma foto empurrando os aquivos para o seu repositório local. Caso vc altere algum arquivos será inciado o ciclho novamente com o aquivo indo para Unmodified.

Repositório
O Git possui dois tipos de repositório, o repositório local que está na sua máquina e o repositório remoto e nada mais é doque o Git Hub que está em núvem sendo que o que você faz no seu repositório loca que fica na sua máquina não repercute imediatamente no seu repositório remoto que é o seu Git Hub, ou seja, para que as alterações realizadas no repositório local reflitam no repositório remoto deverão ser executados um conjunto de códigos específico para tal que irão empurrar essas mudanças para o repositório remoto(Git Hub).

OBS: No abiente de desenvolvimento existe o repositório de trabalho(Working Directory) e tem a Área de Staging, ou seja, os arquivos vão ficar sempre alterando/alternando/movendo entre o repositório de trabalhos e a área de staging na media em que se adciona ou se faz alguma alteração nos arquivos. quando você faz um commit os aquivos passar a fazer parte do seus repositório local ficando aptos a serem empurrados para o seu repositório remoto que nesse caso seria o Git Hub.

Repositório local
É onde ficam os commits prontos para serem empurrados para o repositório remoto(Git Hub).

GIT STATUS
Esse comando vai nos informar o estado dos aquivos  e as alterações realizadas naquele momento sendo necessário a utilização do comando "git add *" para adicionar as alterações jogando os aquivos área de staging a fim de realizar um novo commit jogando esses arquivos para o nosso repositório de trabalho para que após isso possamos empurrar os novos aquivos para o Git Hub atualizando assim o repositório.

Adicionando um arquivo para área de staged
Para se adicionar um arquivo para a área de staged deve se utilizar o seguinte comando: "git add <nomedoarquivo>"

Adicionando vários arquivos para área de staged
Para se adicionar um arquivo para a área de staged deve se utilizar o seguinte comando: "git add * <nomedoarquivo>"

Adicionando arquvo e pasta para área de staged
Para se adicionar um arquivo para a área de staged deve se utilizar o seguinte comando: "git add <nomedoarquivo> nomedapasta/"

Removendo um arquivo da área de staged

para remover um arquivo da área de stageg devesse utilizar o seguinte comando: "git add/rm <nomedoarquivo>"

Restaurando um arquivo na área de staged
Para se restaurar um arquivo da área de staged devesse utilizar o seguinte comando: "git restore <nomedoarquivo>"

Para remover um arquivo da área de stageg para o repositório local devemos criar um commit através da seguinte linha de comando:
"git commit -m "mensagemdo commit"

Criando arquivo dentro de terminal
Para se criar um arquivo direto do terminal deve se utilizar o seguinte comando: echo > "nomedoarquivo.md"



