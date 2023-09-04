# Atividades AWS e Linux 
Repositório de estudos sobre AWS e Linux do Programa de bolsas sobre DevSegOps e AWS.

Esse repositorio contém as atividades sobre linux desenvolvidas do dia 30/08 até 04/09 de 2023.
O escopo das atividades são os seguintes:

**Atividade Teórica:**
- Criar uma apresentação em slides sobre as questões distribuidas para as duplas
- Aplicar os conhecimentos adquiridos na trilha de Linux.
  
**Atividade Prática:**
- Requisitos AWS:
  - Gerar uma chave pública para acesso ao
  ambiente;
  - Criar 1 instância EC2 com o sistema
  operacional Amazon Linux 2 (Família
  t3.small, 16 GB SSD);
  - Gerar 1 elastic IP e anexar à instância EC2;
  - Liberar as portas de comunicação para acesso
  público: (22/TCP, 111/TCP e UDP,
  2049/TCP/UDP, 80/TCP, 443/TCP).
- Requisitos no linux:
  - Configurar o NFS entregue;
  - Criar um diretorio dentro do filesystem do
  NFS com seu nome;
  - Subir um apache no servidor - o apache deve
  estar online e rodando;
  - Criar um script que valide se o serviço esta
  online e envie o resultado da validação para o
  seu diretorio no nfs;
  - O script deve conter - Data HORA + nome do
  serviço + Status + mensagem personalizada de
  ONLINE ou offline;
  - O script deve gerar 2 arquivos de saida: 1 para
  o serviço online e 1 para o serviço OFFLINE;
  - Preparar a execução automatizada do script a
  cada 5 minutos.

- Fazer o versionamento da atividade;
- Fazer a documentação explicando o processo
  de instalação do Linux.

A seguir se encontra os links para o acesso as atividades desenvolvidas.

## Atividade Teórica - Linux

[Atividade Teórica - Linux](https://github.com/AnaMaria27/DevSegOps-e-AWS/blob/master/Linux%20-%20Atividade%20Te%C3%B3ria/AtividadeTeoricaLinux_AnaEClaudio.pdf)

## Atividade Prática - Linux

[Documentação da Atividade Prática sobre Linux](https://github.com/AnaMaria27/DevSegOps-e-AWS/blob/master/Linux%20-%20Atividade%20Pr%C3%A1tica/Documenta%C3%A7%C3%A3o_AtividadePr%C3%A1tica.pdf)

[Script de Verificação do Status do Apache](https://github.com/AnaMaria27/DevSegOps-e-AWS/blob/master/Linux%20-%20Atividade%20Pr%C3%A1tica/status_service.sh.txt)
