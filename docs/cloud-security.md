<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:2563eb&height=180&section=header&text=Cloud%20Security&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=AWS%20%7C%20IAM%20%7C%20Network%20Security%20%7C%20Monitoring&descAlignY=58&descSize=16" width="100%"/>

<div align="center">

<sub>Segurança em ambientes de nuvem, com foco em AWS, identidade, redes, monitoramento e proteção de recursos.</sub>

</div>

---

**visão geral**

Cloud Security aplica os fundamentos de Cybersecurity a ambientes de computação em nuvem.

O objetivo desta etapa é compreender como proteger recursos, identidades, redes, dados e aplicações em ambientes cloud.

A trilha terá foco principalmente em **AWS**, conectando os conhecimentos de:

- Cybersecurity;
- Redes;
- Linux;
- IAM;
- Infraestrutura;
- Monitoramento;
- Logs;
- Automação.

---

**fundamentos de cloud**

Antes de trabalhar diretamente com segurança, é necessário compreender como a computação em nuvem funciona.

**modelos de serviço**

- [ ] IaaS
- [ ] PaaS
- [ ] SaaS
- [ ] Serverless

**modelos de implantação**

- [ ] Public Cloud
- [ ] Private Cloud
- [ ] Hybrid Cloud

**conceitos fundamentais**

- [ ] Regiões
- [ ] Availability Zones
- [ ] Recursos
- [ ] Serviços
- [ ] Escalabilidade
- [ ] Elasticidade
- [ ] Alta disponibilidade
- [ ] Resiliência

---

**modelo de responsabilidade compartilhada**

A segurança na nuvem é dividida entre o provedor e o cliente.

```text
Cloud Provider
      │
      ├── Segurança da infraestrutura
      ├── Datacenters
      ├── Hardware
      └── Infraestrutura física
             │
             ▼
         Cliente
             │
             ├── Identidades
             ├── Permissões
             ├── Dados
             ├── Configurações
             ├── Aplicações
             └── Recursos utilizados
```

Estudar:

- [ ] Responsabilidades do provedor
- [ ] Responsabilidades do cliente
- [ ] Diferenças entre serviços
- [ ] Configurações sob responsabilidade do cliente

---

**aws**

AWS será a principal plataforma cloud utilizada neste roadmap.

Áreas prioritárias:

- [ ] IAM
- [ ] EC2
- [ ] S3
- [ ] VPC
- [ ] Security Groups
- [ ] CloudTrail
- [ ] CloudWatch

O objetivo não é apenas conhecer os serviços, mas compreender como eles podem ser configurados e protegidos.

---

**IAM**

Identity and Access Management controla identidades e permissões dentro da AWS.

**conceitos**

- [ ] Users
- [ ] Groups
- [ ] Roles
- [ ] Policies
- [ ] Permissions
- [ ] Authentication
- [ ] Authorization
- [ ] MFA
- [ ] Least Privilege

**segurança**

- [ ] Evitar permissões excessivas
- [ ] Aplicar menor privilégio
- [ ] Utilizar roles quando apropriado
- [ ] Proteger credenciais
- [ ] Revisar permissões
- [ ] Monitorar atividades
- [ ] Remover acessos desnecessários

**projeto relacionado**

[→ IAM Security Lab](../projects/iam-security-lab.md)

---

**EC2**

Amazon EC2 fornece capacidade computacional na nuvem.

Estudar:

- [ ] Instâncias
- [ ] AMIs
- [ ] Tipos de instância
- [ ] Storage
- [ ] Security Groups
- [ ] SSH
- [ ] Atualizações
- [ ] Hardening
- [ ] Monitoramento

**segurança**

- [ ] Princípio do menor privilégio
- [ ] Restringir portas
- [ ] Atualizar sistema
- [ ] Utilizar autenticação adequada
- [ ] Monitorar atividades
- [ ] Evitar exposição desnecessária

---

**S3**

Amazon S3 é utilizado para armazenamento de objetos.

Estudar:

- [ ] Buckets
- [ ] Objects
- [ ] Permissions
- [ ] Policies
- [ ] Versioning
- [ ] Encryption
- [ ] Access Control

**segurança**

- [ ] Evitar exposição pública desnecessária
- [ ] Controlar permissões
- [ ] Proteger dados
- [ ] Utilizar criptografia
- [ ] Monitorar acesso
- [ ] Revisar policies

---

**VPC**

Amazon VPC permite criar uma rede virtual isolada dentro da AWS.

Estudar:

- [ ] VPC
- [ ] Subnets
- [ ] Route Tables
- [ ] Internet Gateway
- [ ] NAT Gateway
- [ ] Security Groups
- [ ] Network ACLs
- [ ] Endereçamento IP
- [ ] Roteamento

Estrutura conceitual:

```text
AWS
 │
 └── VPC
      │
      ├── Public Subnet
      │     └── Recursos públicos
      │
      └── Private Subnet
            └── Recursos privados
```

---

**security groups**

Security Groups funcionam como controles de tráfego associados a recursos.

Estudar:

- [ ] Inbound Rules
- [ ] Outbound Rules
- [ ] Portas
- [ ] Protocolos
- [ ] IPs
- [ ] Referências entre Security Groups
- [ ] Princípio do menor privilégio

Objetivo:

> Permitir somente o tráfego necessário para o funcionamento do recurso.

---

**cloudtrail**

AWS CloudTrail registra atividades relacionadas à conta e aos serviços AWS.

Estudar:

- [ ] Eventos
- [ ] API Calls
- [ ] Users
- [ ] Roles
- [ ] Resources
- [ ] Timestamps
- [ ] Event History
- [ ] Trails
- [ ] Detecção baseada em eventos

Fluxo:

```text
Atividade AWS
      ↓
CloudTrail
      ↓
Evento
      ↓
Análise
      ↓
Detecção
      ↓
Investigação
      ↓
Resposta
```

**projeto relacionado**

[→ CloudTrail Detection Lab](../projects/cloudtrail-detection-lab.md)

---

**cloudwatch**

Amazon CloudWatch fornece recursos para monitoramento e observabilidade.

Estudar:

- [ ] Metrics
- [ ] Logs
- [ ] Alarms
- [ ] Dashboards
- [ ] Monitoramento de recursos
- [ ] Eventos
- [ ] Alertas

O objetivo é conectar observabilidade com segurança.

---

**logging e monitoramento**

Uma arquitetura de segurança cloud precisa produzir evidências para análise.

```text
AWS Resources
      ↓
Logs / Events
      ↓
Collection
      ↓
Monitoring
      ↓
Detection
      ↓
Alert
      ↓
Investigation
```

Estudar:

- [ ] Centralização de logs
- [ ] Retenção
- [ ] Integridade
- [ ] Monitoramento
- [ ] Alertas
- [ ] Correlação
- [ ] Investigação

---

**cloud security posture**

A segurança de um ambiente cloud depende também da configuração correta dos recursos.

Verificar:

- [ ] IAM
- [ ] Storage
- [ ] Network
- [ ] Logging
- [ ] Encryption
- [ ] Monitoring
- [ ] Public Exposure
- [ ] Permissions
- [ ] Security Groups
- [ ] Recursos não utilizados

Objetivo:

> Identificar configurações que aumentam a superfície de exposição e aplicar controles adequados.

---

**hardening**

Hardening consiste em reduzir possibilidades desnecessárias de exposição.

Exemplos:

- [ ] Remover recursos não utilizados
- [ ] Restringir permissões
- [ ] Restringir portas
- [ ] Atualizar sistemas
- [ ] Proteger credenciais
- [ ] Ativar monitoramento
- [ ] Habilitar logs
- [ ] Utilizar criptografia
- [ ] Revisar configurações

---

**cloud security architecture**

Modelo conceitual:

```text
                    AWS
                     │
             ┌───────┴───────┐
             │               │
            IAM             VPC
             │               │
       Permissions      Network Controls
             │               │
             └───────┬───────┘
                     │
                  Resources
                     │
          ┌──────────┴──────────┐
          │                     │
        Logging              Monitoring
          │                     │
          └──────────┬──────────┘
                     │
                  Detection
                     │
                  Response
```

---

**laboratórios**

A prática será realizada em ambientes controlados.

**Cloud Security Lab**

- [ ] Criar arquitetura cloud básica
- [ ] Configurar recursos
- [ ] Aplicar controles
- [ ] Revisar exposição
- [ ] Documentar arquitetura

[→ Cloud Security Lab](../projects/cloud-security-lab.md)

**IAM Security Lab**

- [ ] Criar identidades
- [ ] Criar policies
- [ ] Aplicar menor privilégio
- [ ] Testar permissões
- [ ] Documentar decisões

[→ IAM Security Lab](../projects/iam-security-lab.md)

**CloudTrail Detection Lab**

- [ ] Gerar eventos controlados
- [ ] Coletar registros
- [ ] Identificar eventos
- [ ] Criar lógica de detecção
- [ ] Documentar investigação

[→ CloudTrail Detection Lab](../projects/cloudtrail-detection-lab.md)

---

**integração com cybersecurity**

Os conhecimentos anteriores serão utilizados diretamente.

```text
Linux
  │
  ├── Administração
  └── Logs
       │
       ▼
Redes
  │
  ├── TCP/IP
  └── Segurança de rede
       │
       ▼
Cybersecurity
  │
  ├── IAM
  ├── Vulnerabilidades
  └── Monitoramento
       │
       ▼
AWS
  │
  ├── VPC
  ├── IAM
  ├── CloudTrail
  └── CloudWatch
```

---

**checklist**

**cloud fundamentals**

- [ ] IaaS
- [ ] PaaS
- [ ] SaaS
- [ ] Regiões
- [ ] Availability Zones
- [ ] Responsabilidade compartilhada

**AWS**

- [ ] IAM
- [ ] EC2
- [ ] S3
- [ ] VPC
- [ ] Security Groups
- [ ] CloudTrail
- [ ] CloudWatch

**security**

- [ ] Least Privilege
- [ ] Hardening
- [ ] Logging
- [ ] Monitoring
- [ ] Encryption
- [ ] Access Control

**prática**

- [ ] Cloud Security Lab
- [ ] IAM Security Lab
- [ ] CloudTrail Detection Lab

---

**próxima etapa**

Depois de Cloud Security, o roadmap avança para a organização do **portfólio técnico**, conectando conhecimentos, projetos, documentação e evidências práticas.

[← Voltar para o Roadmap](roadmap.md)

[← Cybersecurity](cybersecurity.md)

[→ Portfólio](portfolio.md)

---

<div align="center">

<sub>AWS • Cloud Security • IAM • Networking • Monitoring</sub>

</div>
