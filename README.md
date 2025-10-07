# RELATÓRIO DE IMPLEMENTAÇÃO DE MEDIDAS DE SEGURANÇA
**Data:** 07 de outubro de 2025

**Empresa:** Abstergo Industries

**Responsável:** Caio Bukvar Fernandes

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa *Abstergo Industries*, realizado por *Caio Bukvar Fernandes*. O objetivo do projeto foi elencar 03 medidas de segurança em conjunto dos serviços AWS, com a finalidade de aumentar a segurança na empresa.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 03 medidas de segurança. A seguir, serão descritas as etapas da implementação:

### Medida 01: Proteção de Infraestrutura e Aplicações Web
**Ferramentas: *Amazon GuardDuty + AWS WAF***

**Descrição de caso de uso:** Implementação do Amazon GuardDuty para monitoramento contínuo de ameaças na infraestrutura AWS, identificando atividades maliciosas, acessos não autorizados e comportamentos anômalos em contas, instâncias EC2 e dados armazenados. Em conjunto, o AWS WAF (Web Application Firewall) foi configurado para proteger as aplicações web contra ataques comuns como SQL Injection, Cross-Site Scripting (XSS) e bots maliciosos, criando regras customizadas de filtragem de tráfego HTTP/HTTPS.

**Benefícios:**
- Detecção automatizada de ameaças em tempo real
- Proteção contra ataques OWASP Top 10
- Redução de superfície de ataque em aplicações webAlertas proativos sobre atividades suspeitas

### Medida 02: Gerenciamento Seguro de Identidades e Acessos
**Ferramentas: *AWS IAM + Multi-Factor Authentication (MFA)***

**Descrição de caso de uso:** Estruturação de políticas de acesso baseadas no princípio do menor privilégio através do AWS Identity and Access Management (IAM), criando grupos, roles e políticas granulares para cada função na organização. Implementação obrigatória de autenticação multifator (MFA) para todos os usuários com acesso ao console AWS e para operações sensíveis via CLI/API, utilizando dispositivos virtuais ou físicos de autenticação.

**Benefícios:**
- Controle granular de permissões por usuário e serviço
- Proteção contra comprometimento de credenciais
- Rastreabilidade de ações por usuário
- Conformidade com políticas de segurança corporativa
- Redução de riscos de acesso não autorizado

### Medida 03: Monitoramento e Auditoria de Segurança
**Ferramentas: *AWS CloudTrail + Amazon CloudWatch + CloudTrail Insights***

**Descrição de caso de uso:** Ativação do AWS CloudTrail para registro completo de todas as chamadas de API realizadas na conta AWS, criando uma trilha de auditoria imutável. Integração com Amazon CloudWatch para criação de alarmes personalizados sobre eventos críticos de segurança (falhas de login, alterações em security groups, modificações em buckets S3, etc.). Habilitação do CloudTrail Insights para detecção automática de atividades anômalas e padrões incomuns de uso de recursos.

**Benefícios:**
- Auditoria completa de ações realizadas na infraestrutura
- Detecção proativa de anomalias operacionais
- Conformidade com requisitos regulatórios (LGPD, SOC 2, ISO 27001)
- Resposta rápida a incidentes de segurança
- Visibilidade completa sobre mudanças na infraestrutura

## Conclusão
A implementação das medidas na empresa Abstergo Industries tem como esperado o estabelecimento de uma postura de segurança robusta e em múltiplas camadas (defesa em profundidade). As ferramentas implementadas proporcionarão proteção contra ameaças externas e internas, controle rigoroso de acessos e visibilidade completa sobre todas as atividades realizadas na infraestrutura AWS.

**Os impactos esperados incluem:**
- Redução significativa de riscos de segurança cibernética
- Detecção e resposta acelerada a incidentes
- Conformidade com frameworks de segurança e regulamentações
- Maior confiança de clientes e parceiros
- Proteção de ativos críticos e dados sensíveis da organização

**Assinatura do Responsável:**

Caio Bukvar Fernandes

Data: 07/10/2025










