# RELATÓRIO DE IMPLEMENTAÇÃO DE MEDIDAS DE SEGURANÇA

Data: 09/09/2023
Empresa: Abstergo Industries 
Responsável: Loyanne Moreira dos Santos

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Loyanne Moreira dos Santos. O objetivo do projeto foi elencar 3 medidas de segurança em conjunto dos serviços da AWS, com a finalidade de realizar aumentar a segurança na empresa.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 medidas de segurança. A seguir, serão descritas as etapas da implementação:

Medida 1: **Implementação de AWS Identity and Access Management (IAM) com Autenticação Multifatorial (MFA)**
- *Descrição de caso de uso*
    - Ao configurar o AWS IAM com autenticação multifatorial (MFA), você adiciona uma camada adicional de segurança à sua conta AWS. Isso é especialmente importante para proteger contas de usuário com privilégios administrativos. Com o MFA habilitado, os usuários precisam fornecer não apenas suas credenciais de login, mas também um código temporário gerado por um dispositivo MFA, como um aplicativo de autenticação ou um token físico. Isso torna muito mais difícil para invasores comprometerem contas de usuário, mesmo que tenham acesso às credenciais de login. Essa medida ajuda a evitar brechas de segurança de alto risco.

Medida 2: **Configuração de AWS GuardDuty para detecção de ameaças em tempo real**
- *Descrição de caso de uso*
    - O AWS GuardDuty é um serviço de detecção de ameaças gerenciado que monitora continuamente a atividade da sua conta AWS em busca de comportamentos maliciosos e indicadores de comprometimento. Ele usa técnicas de aprendizado de máquina para identificar ameaças, como tentativas de acesso não autorizado, varreduras de portas e atividades de malware. Configurando o GuardDuty, você pode receber alertas em tempo real sobre possíveis ameaças à sua infraestrutura. Isso permite que você responda rapidamente a incidentes de segurança e tome medidas para mitigar riscos de forma proativa.

Medida 3: **Implementação de Grupos de Segurança de Rede e Listas de Controle de Acesso (ACLs)**
- *Descrição de caso de uso*
    - Os Grupos de Segurança de Rede (Security Groups) e Listas de Controle de Acesso (Network ACLs) são recursos essenciais para controlar o tráfego de rede em sua infraestrutura na AWS. Você pode usar os Security Groups para definir regras de firewall em nível de instância, controlando quais protocolos e portas são permitidos ou bloqueados. As Network ACLs operam em nível de sub-rede e permitem controlar o tráfego de entrada e saída em uma camada mais ampla. A combinação de ambos os recursos ajuda a criar camadas adicionais de segurança em sua infraestrutura, protegendo contra ataques de rede.


## Conclusão
A implementação de ferramentas na empresa *Abstergo Industries tem como esperado fortalecer a postura de segurança da empresa na nuvem, protegendo os recursos, os dados e as operações críticas contra ameaças cibernéticas*, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos
Acesse mais informações sobre [autenticação multifator (MFA) para o IAM](https://aws.amazon.com/pt/iam/features/mfa/#:~:text=A%20autentica%C3%A7%C3%A3o%20multifator%20(MFA)%20da,nome%20de%20usu%C3%A1rio%20e%20senha.) no site da AWS. 

Acesse mais informações sobre o [GuardDuty](https://aws.amazon.com/pt/guardduty/) no site da AWS. 

Acesse mais informações sobre o [Grupos de Segurança de Rede e Listas de Controle de Acesso (ACLs)](https://docs.aws.amazon.com/pt_br/whitepapers/latest/aws-best-practices-ddos-resiliency/security-groups-and-network-access-control-lists-nacls-bp5.html) no site da AWS. 


Assinatura do Responsável pelo Projeto:
Loyanne Moreira dos Santos
(AWS Certified Cloud Practitioner)