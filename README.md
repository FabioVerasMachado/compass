# Atividade01-AWS
![Alt text](images/AWS.jpeg)

:rocket: Primeira Tarefa do Estágio Compass-UOL DevSecOps AWS
:page_facing_up: Descrição

Este projeto tem como objetivo avaliar os conhecimentos adquiridos durante a Trilha Compass-UOL, focada na preparação para a certificação "AWS Certified Cloud Practitioner". A tarefa envolve a realização de atividades práticas em um ambiente AWS, com foco na configuração de infraestrutura em nuvem e automação de tarefas seguindo boas práticas de DevSecOps.
:hammer_and_wrench: Instruções de Instalação e Execução
Parte Prática:

>> **Gerar Chave de Acesso:**
        Gerar uma chave pública para acessar o ambiente AWS.

>> **Configuração da Instância EC2:** 
        Criar uma instância EC2 com o sistema operacional Amazon Linux 2 (t3.small, 16 GB SSD).
        Associar um Elastic IP à instância.

>> **Cofiguração de Segurança:**
        Liberar as seguintes portas de comunicação para acesso público:
            22/TCP: Acesso SSH.
            111/TCP/UDP: Utilizado pelo NFS.
            2049/TCP/UDP: Utilizado pelo NFS.
            80/TCP: Acesso HTTP.
            443/TCP: Acesso HTTPS.

>> **Configuração do NFS:**
        Configurar o sistema de arquivos NFS.
        Criar um diretório no NFS com o seu nome para armazenar os resultados do monitoramento.

>> **Implementação do Apache:**
        Instalar e configurar o servidor Apache, garantindo que ele esteja rodando e acessível publicamente.

>> **Monitoramento de Serviço:**
        Criar um script para validar o status do serviço Apache e gerar um log. O script deve:
            Exibir Data e Hora, Nome do Serviço, Status (ONLINE/OFFLINE) e uma mensagem personalizada.
            Gerar dois arquivos de saída:
                Um para quando o serviço estiver ONLINE.
                Outro para quando estiver OFFLINE.

>> **Automação:**
        Automatizar a execução do script a cada 5 minutos utilizando o cron.

>> **Versionamento:**
        Versionar o projeto utilizando o sistema de controle de versões Git.

>> **Documentação:**
        Incluir uma documentação clara e detalhada, explicando o processo de instalação e configuração dos serviços no Linux.


**Requisitos**

    Ambiente: AWS Cloud Computing.
    Ferramentas Utilizadas:
        EC2 (Amazon Linux 2)
        Elastic IP
        NFS
        Servidor Apache
        Scripts de monitoramento e cron

**Problemas Conhecidos / Bugs**

    Durante a execução da tarefa, alguns desafios foram enfrentados, especialmente em relação à familiaridade com o Console da AWS e à necessidade de relembrar habilidades previamente adquiridas.
    O principal obstáculo foi a automação do script de monitoramento, que apresentou diferenças de comportamento quando executado localmente no VirtualBox em comparação ao ambiente AWS. A solução foi integrar o monitoramento diretamente ao cron, permitindo o correto funcionamento tanto localmente quanto na AWS.

 **Histórico de Versões**

    Versão 1.0 (Primeira Versão - Primeiro Projeto):
        Esta é a primeira versão do projeto, realizada como parte da primeira tarefa do estágio DevSecOps Compass-UOL, envolvendo a configuração e automação de infraestrutura no ambiente AWS.

>> **Contato**

    Autor: Fábio Veras
    E-mail: fabioverasmachado@hotmail.com



[def]: images/CompassUOL.jpeg
