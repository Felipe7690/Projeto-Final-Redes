# Projeto Final de Administração de Redes de Computadores

## Topologia da Rede

## Seguimentação de Sub-Redes

## Requisitos

## Scripts 

## Descrição das Redes 

## Configurações 

## Resultados dos Testes 


# Projeto de Rede - Documentação

## Rede Empresarial com Tecnologia Linux

Este projeto visa projetar, implantar e gerenciar uma rede empresarial usando tecnologia Linux. A infraestrutura será construída com ênfase em serviços como DHCP, DNS, Web, FTP, NFS, e será virtualizada utilizando Vagrant e Docker.

## Etapa 01 - Estrutura Documental (Data de Entrega: 23/11/2023)

### Topologia de Rede

A topologia da rede será configurada para um ambiente empresarial com três sub-redes...

### Segmentação de Sub-redes

1. **Sub-rede 1:**
   - Faixa de IP: 192.168.1.0/24
   - Serviços: DHCP (atribuição de IPs estáticos)

2. **Sub-rede 2:**
   - Faixa de IP: 192.168.2.0/24
   - Serviços: DNS, Web (Apache ou Nginx), FTP, NFS

3. **Sub-rede 3:**
   - Faixa de IP: 192.168.3.0/24
   - Serviço: DHCP (atribuição de IPs dinâmicos)

### Requisitos de Serviços

- **DHCP:**
  - Atribuir IPs estáticos (Sub-rede 1) e dinâmicos (Sub-rede 3).

- **DNS:**
  - Resolução de nomes de domínio e configuração de registros.

- **Web:**
  - Hospedagem interna de sites usando Apache ou Nginx.

- **FTP:**
  - Configuração do servidor vsftpd para transferência de arquivos.

- **NFS:**
  - Compartilhamento de diretórios entre máquinas (Sub-rede 2).

### Virtualização e Containerização

Utilização do Vagrant para criar máquinas virtuais e Docker para implantar aplicativos em contêineres.

### Documentação no Git

Todo o processo de configuração será documentado no [repositório Git](link_para_o_repositorio), incluindo...

## Etapa 02 - Implementação (Data de Entrega: 30/11/2023 em diante)

### Configuração do Servidor DHCP

- Configuração do servidor DHCP no ambiente Linux para atribuição de IPs automáticos.

### Implementação do Servidor DNS

- Configuração do servidor DNS para resolução de nomes de domínio.

### Configuração do Servidor Web

- Hospedagem de sites internos utilizando Apache ou Nginx.

### Configuração do Servidor FTP

- Implementação do servidor vsftpd para transferência de arquivos.

### Configuração do Servidor NFS

- Configuração do servidor NFS para compartilhamento de diretórios.

---

A documentação será continuamente atualizada durante o processo de implementação, detalhando cada etapa, configuração realizada e resultados obtidos nos testes.

