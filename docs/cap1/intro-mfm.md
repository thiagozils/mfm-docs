---
sidebar_position: 1
---

# Descrição do WEG MFM

Apresentação dos elementos gerais do WEG MFM, metodologia e finalidade, descrição das principais funções do produto, dedicada ao usuário que irá operar o WEG MFM.

## O que é o WEG MFM ?

O WEG MFM é um software de gestão do conjunto de ativos instalados em uma ou mais plantas, em um único ou em vários sites (multi-sites). Consiste em um gerenciador que permite a conexão com os ativos da frota para serem monitorados, fazendo a gestão dos mesmos. Você pode monitorar e atribuir as seguintes informações no WEG MFM:

-	Informações de status da unidade / planta / ativo / sensores;
-	Indicadores de performance como temperatura, vibração, tempo de operação, entre outros.
-	Informações relativas à saúde e manutenção;
-	Histórico de operação;
-	Falhas e intervenções;
-	Alarmes e avisos;
-	Relatórios diários e mensais.

## Segurança de dados

O WEG MFM utiliza mecanismos de criptografia para os dados. Durante o transporte, a comunicação entre dispositivos é criptografada usando TLS, esquema padrão do setor e largamente utilizado. 

A segurança também é aplicada ao acesso à API por autenticação JSON Web Tokens padrão. O WEG MFM não armazena os tokens depois de gerados. Cabe ao usuário salvar essas informações com segurança. Os dispositivos que se comunicam usando MQTT usam segredos e chaves do aplicativo e são implementados da mesma maneira que os Tokens da API, mas acessam automaticamente o escopo da aplicação específica. A segurança de infraestrutura é feita usando a funcionalidade de disco persistente do Google Compute Engine, que criptografa todos os dados em trânsito e em repouso.  

Para proteger as plantas, sistemas, máquinas e redes contra-ataques cibernéticos, é necessário a implementação da manutenção de forma contínua e completa. 


