# LLM_NAO_DOCKER


Tabela de conteúdos
=================
<!--ts-->
   * [Sobre](#sobre)
   * [Pré-Requisitos](#pré-requisitos)
   * [Instalação](#instalação)
<!--te-->

## Sobre
Conteinerização do projeto "https://github.com/Samuellps/NAO", que tem como objetivo de desenvolver a função de diálogo com o robô NAO da por meio da implementação de uma LLM.

## Pré-Requisitos
Para criar um container do projeto, é preciso clonar o projeto em uma pasta, isto pode ser feito com o comando:<br/><br/>
`git clone https://github.com/viniciustormin/LLM_NAO_DOCKER.git`<br/><br/>
Também será preciso ter o Docker Desktop instalado no computador, caso não tenha, baixe por este [link](https://www.docker.com/products/docker-desktop/).
Por fim, será necessário que o seu computador tenha arquitetura AMD64.

## Instalação
Para construir e iniciar o container da aplicação, será necessário, primeiramente, abrir o programa do Docker Desktop e deixa-lo aberto, então abrir o terminal e navegar até a pasta clonada utilizando o comando:<br/><br/>
`cd .../LLM_NAO_DOCKER`<br/><br/>
Então construimos o container utilizando o comando:<br/><br/>
`docker build -t LLM_NAO_DOCKER .`<br/><br/>
Assim o container começará o processo de construção, e ao fim, poderemos iniciar o container com o comando:<br/><br/>
`docker run -it LLM_NAO_DOCKER`<br/><br/>
Com o container rodando e aberto em seu terminal, é possivel transitar entre os programas rodados em Python 3 e Python 2.7 utilizando o atalho `Ctrl+B` e em seguida pressionar os numerais `0` e `1` para transitar entre os terminais do container.
