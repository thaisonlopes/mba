
Caso ocorra o seguinte erro: Cannot start service : Ports are not available: listen tcp 0.0.0.0:50070:

Executar o CMD como administrador e executar o comando abaixo.

net stop winnat

Clonando o repositório do cartola para a pasta do projeto

git clone https://github.com/wgenial/cartrolandofc.git

Estrutura de pastas:

- fiap-challenge-1
    - bigdata_docker
    - data
        - cartola

Comandos HDFS:
- hadoop fs -ls / (Listar arquivos no hadoop fs)

- hadoop fs -mkdir /cartola (criar diretorio de nome /cartola no hdfs)

- hadoop fs -cat /path/to/teste.csv (Executar o comando -cat em um arquivo de nome teste.csv)

- hadoop fs -ls /cartola (Listar arquivos de dentro da pasta cartola)

- hadoop fs -rm /cartola/teste.csv (Remove o arquivo teste.csv presente na pasta cartola)

- hadoop fs -put /cartola/* /cartola (Copiar os arquivos da pasta /cartola local para o caminho /cartola no hdfs)

Baixando os arquivos para o hadoop cluster:

1. Pergunta: Qual a maneira correta de conectar a um Cluster Hadoop de uma aplicação?

2. Pergunta: Qual a maneira correta de baixar os dados programaticamente a um Cluster Hadoop de uma aplicação?

HDFS comando pra upload de arquivos:
hadoop fs -put /cartola/* /cartola

Baixando arquivos do github
https://gist.github.com/Integralist/9482061

Criar um Dockerfile pra raiz do projeto.

- Criar tabela no Hive