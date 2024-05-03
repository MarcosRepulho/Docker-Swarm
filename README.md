# Este repositório GitHub contém um projeto Docker Swarm desenvolvido por Marcos Repulho. O Docker Swarm é uma ferramenta de orquestração de containers que permite gerenciar e escalar aplicativos em containers em vários hosts.





# Funcionalidades:

Gerenciamento de containers: O Swarm permite iniciar, parar, remover e gerenciar containers em vários hosts.
Escalabilidade: O Swarm pode escalar aplicativos automaticamente adicionando ou removendo containers conforme a demanda.
Alta disponibilidade: O Swarm pode garantir que os aplicativos estejam sempre disponíveis, mesmo em caso de falha de um host.
Descoberta de serviços: O Swarm permite que os containers se comuniquem entre si facilmente, sem a necessidade de configurar endereços IP manualmente.
Requisitos:

>Docker instalado em todos os hosts
>Uma rede privada para comunicação entre os hosts


Read.ME: Docker Swarm
Este repositório GitHub contém um projeto Docker Swarm desenvolvido por Marcos Repulho. O Docker Swarm é uma ferramenta de orquestração de containers que permite gerenciar e escalar aplicativos em containers em vários hosts.

# Funcionalidades:

Gerenciamento de containers: O Swarm permite iniciar, parar, remover e gerenciar containers em vários hosts.
Escalabilidade: O Swarm pode escalar aplicativos automaticamente adicionando ou removendo containers conforme a demanda.
Alta disponibilidade: O Swarm pode garantir que os aplicativos estejam sempre disponíveis, mesmo em caso de falha de um host.
 Descoberta de serviços: O Swarm permite que os containers se comuniquem entre si facilmente, sem a necessidade de configurar endereços IP manualmente.

## Requisitos:

> ## Docker instalado em todos os hosts
Uma rede privada para comunicação entre os hosts
Instalação:

Clone o repositório GitHub:

git clone git@github.com:MarcosRepulho/Docker-Swarm.git

Acesse o diretório do projeto:

cd Docker-Swarm

Inicie o Swarm:

docker swarm init

Adicione os hosts de trabalho ao Swarm:

> docker swarm join --token <token-de-trabalho> <endereço-do-host-de-trabalho>


# Uso:

> Para iniciar um container, use o comando docker run.
  Para gerenciar containers, use o comando docker ps.
  Para escalar um aplicativo, use o comando docker service create.
> Para visualizar logs de containers, use o comando docker logs.
