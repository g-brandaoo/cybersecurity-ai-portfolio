<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:2563eb&height=180&section=header&text=Cybersecurity&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Security%20Fundamentals%20%7C%20Attack%20Surface%20%7C%20Defense%20%7C%20Offense&descAlignY=58&descSize=16" width="100%"/>

<div align="center">

<sub>Fundamentos de segurança, análise de ameaças, segurança ofensiva e defensiva.</sub>

</div>

---

**visão geral**

Cybersecurity é a etapa central do roadmap responsável por aplicar os fundamentos de Linux, redes, programação e Git/GitHub à proteção de sistemas, aplicações, dados e infraestrutura.

O objetivo desta etapa é compreender:

- como sistemas podem ser atacados;
- quais recursos precisam ser protegidos;
- como identificar vulnerabilidades;
- como detectar atividades suspeitas;
- como reduzir riscos;
- como investigar eventos;
- como documentar problemas e controles de segurança.

A abordagem combina conhecimentos de **Red Team, Blue Team, SOC, AppSec e segurança de infraestrutura**.

---

**fundamentos de segurança**

Antes de estudar ferramentas, é necessário compreender os princípios que orientam a segurança.

**tríade CIA**

- [ ] Confidentiality — Confidencialidade
- [ ] Integrity — Integridade
- [ ] Availability — Disponibilidade

**outros conceitos**

- [ ] Autenticação
- [ ] Autorização
- [ ] Controle de acesso
- [ ] Identidade
- [ ] Princípio do menor privilégio
- [ ] Defesa em profundidade
- [ ] Gestão de riscos
- [ ] Vulnerabilidade
- [ ] Ameaça
- [ ] Risco
- [ ] Exploit
- [ ] Mitigação
- [ ] Monitoramento

---

**attack surface**

A Attack Surface representa o conjunto de pontos pelos quais um sistema, aplicação ou infraestrutura pode ser exposto a ameaças.

Exemplos:

- [ ] Serviços de rede
- [ ] Aplicações web
- [ ] APIs
- [ ] Contas de usuários
- [ ] Interfaces administrativas
- [ ] Dispositivos
- [ ] Servidores
- [ ] Recursos de cloud
- [ ] Dependências
- [ ] Repositórios
- [ ] Integrações externas
- [ ] Sistemas de terceiros

**objetivo**

Aprender a identificar, organizar e reduzir superfícies de exposição dentro de ambientes controlados e autorizados.

**projeto relacionado**

[→ Attack Surface Lab](../projects/attack-surface-lab.md)

---

**vulnerabilidades**

Uma vulnerabilidade é uma fraqueza que pode permitir impacto sobre a confidencialidade, integridade ou disponibilidade de um sistema.

Estudo:

- [ ] Vulnerabilidades de software
- [ ] Configurações inseguras
- [ ] Falhas de autenticação
- [ ] Falhas de autorização
- [ ] Exposição de informações
- [ ] Dependências vulneráveis
- [ ] Secrets expostos
- [ ] Erros de configuração
- [ ] Falhas de validação
- [ ] Vulnerabilidades web

---

**web security**

Aplicações web representam uma parte importante da superfície de ataque moderna.

**fundamentos**

- [ ] HTTP
- [ ] HTTPS
- [ ] Cookies
- [ ] Sessões
- [ ] Headers
- [ ] APIs
- [ ] Autenticação
- [ ] Autorização
- [ ] Validação de entrada

**OWASP**

- [ ] Conhecer o OWASP Top 10
- [ ] Estudar categorias de vulnerabilidades
- [ ] Identificar causas
- [ ] Compreender impactos
- [ ] Estudar mitigação
- [ ] Praticar em ambientes autorizados

**projeto relacionado**

[→ Web Vulnerability Lab](../projects/web-vulnerability-lab.md)

---

**red team**

Red Team representa a perspectiva ofensiva utilizada para avaliar a segurança de ambientes autorizados.

O objetivo no roadmap é compreender técnicas ofensivas para identificar problemas e melhorar as defesas.

Áreas de estudo:

- [ ] Reconhecimento
- [ ] Mapeamento de superfície
- [ ] Identificação de serviços
- [ ] Análise de aplicações
- [ ] Identificação de vulnerabilidades
- [ ] Exploração em laboratórios
- [ ] Pós-exploração em ambientes controlados
- [ ] Relatórios técnicos
- [ ] Recomendações de mitigação

Toda prática ofensiva deve ocorrer somente em ambientes próprios, autorizados ou especificamente destinados a treinamento.

---

**blue team**

Blue Team representa a perspectiva defensiva.

O foco está em prevenir, detectar, investigar e responder a eventos de segurança.

Áreas de estudo:

- [ ] Hardening
- [ ] Controle de acesso
- [ ] Monitoramento
- [ ] Logs
- [ ] Detecção
- [ ] Alertas
- [ ] Threat Detection
- [ ] Incident Response
- [ ] Análise de eventos
- [ ] Investigação
- [ ] Recuperação

---

**SOC**

Um Security Operations Center reúne processos, pessoas e tecnologias voltados ao monitoramento e resposta a eventos de segurança.

Conceitos:

- [ ] Monitoramento contínuo
- [ ] Coleta de logs
- [ ] SIEM
- [ ] Alertas
- [ ] Eventos
- [ ] Indicadores de comprometimento
- [ ] Correlação
- [ ] Triagem
- [ ] Investigação
- [ ] Escalonamento
- [ ] Resposta a incidentes

**projetos relacionados**

[→ SOC Home Lab](../projects/soc-home-lab.md)

[→ SIEM + Logs Lab](../projects/siem-logs-lab.md)

---

**logs e monitoramento**

Logs fornecem informações sobre atividades realizadas em sistemas e aplicações.

Estudar:

- [ ] Tipos de logs
- [ ] Logs de sistema
- [ ] Logs de autenticação
- [ ] Logs de aplicações
- [ ] Logs de rede
- [ ] Logs de cloud
- [ ] Timestamps
- [ ] Eventos
- [ ] Correlação
- [ ] Retenção
- [ ] Alertas

Fluxo básico:

```text
Evento
   ↓
Log
   ↓
Coleta
   ↓
Análise
   ↓
Correlação
   ↓
Detecção
   ↓
Investigação
   ↓
Resposta
```

---

**threat modeling**

Threat Modeling permite analisar antecipadamente possíveis ameaças e pontos de risco.

Estudar:

- [ ] Identificação de ativos
- [ ] Identificação de entradas
- [ ] Identificação de componentes
- [ ] Identificação de ameaças
- [ ] Análise de riscos
- [ ] Controles de segurança
- [ ] Mitigações
- [ ] Revisão do modelo

Fluxo:

```text
Ativos
  ↓
Arquitetura
  ↓
Superfície de ataque
  ↓
Ameaças
  ↓
Riscos
  ↓
Controles
  ↓
Mitigações
```

---

**defesa em profundidade**

A segurança não deve depender de um único mecanismo.

Exemplo conceitual:

```text
Identidade
    ↓
Controle de acesso
    ↓
Firewall
    ↓
Hardening
    ↓
Monitoramento
    ↓
Detecção
    ↓
Resposta
```

Se uma camada falhar, outras podem reduzir o impacto.

---

**segurança de identidade**

Identidade é um componente central da segurança moderna.

Estudar:

- [ ] Usuários
- [ ] Grupos
- [ ] Roles
- [ ] Autenticação
- [ ] MFA
- [ ] Autorização
- [ ] Permissões
- [ ] Privilégio mínimo
- [ ] Gestão de credenciais
- [ ] Gestão de secrets

Este conhecimento será aprofundado posteriormente em **Cloud Security e IAM**.

---

**criptografia**

Fundamentos necessários:

- [ ] Criptografia simétrica
- [ ] Criptografia assimétrica
- [ ] Chaves
- [ ] Hash
- [ ] Assinaturas digitais
- [ ] Certificados
- [ ] TLS
- [ ] Gestão de chaves

O objetivo é compreender quando e por que cada mecanismo é utilizado.

---

**security mindset**

A segurança exige uma abordagem baseada em questionamento e análise.

Perguntas importantes:

```text
O que estou protegendo?

Quem pode acessar?

Como esse acesso acontece?

O que aconteceria se esse controle falhasse?

Como eu detectaria essa falha?

Como eu reduziria o impacto?

Como eu provaria que o controle está funcionando?
```

Essa mentalidade será aplicada aos projetos do repositório.

---

**projetos desta etapa**

| Projeto | Foco |
|---|---|
| Attack Surface Lab | Superfície de ataque |
| Web Vulnerability Lab | Segurança web |
| SOC Home Lab | Monitoramento e SOC |
| SIEM + Logs Lab | Logs e detecção |

---

**progressão prática**

```text
Fundamentos
     ↓
Attack Surface
     ↓
Vulnerabilidades
     ↓
Web Security
     ↓
Red Team
     ↓
Blue Team
     ↓
SOC
     ↓
Detecção
     ↓
Incident Response
```

A progressão permite compreender tanto a perspectiva ofensiva quanto a defensiva.

---

**checklist**

**fundamentos**

- [ ] CIA
- [ ] Autenticação
- [ ] Autorização
- [ ] Controle de acesso
- [ ] Vulnerabilidades
- [ ] Riscos
- [ ] Mitigações

**attack surface**

- [ ] Identificação de ativos
- [ ] Identificação de exposição
- [ ] Mapeamento
- [ ] Redução de superfície

**segurança web**

- [ ] HTTP/HTTPS
- [ ] Sessões
- [ ] APIs
- [ ] OWASP
- [ ] Vulnerabilidades
- [ ] Mitigações

**defesa**

- [ ] Logs
- [ ] Monitoramento
- [ ] SIEM
- [ ] Detecção
- [ ] SOC
- [ ] Incident Response

**prática**

- [ ] Attack Surface Lab
- [ ] Web Vulnerability Lab
- [ ] SOC Home Lab
- [ ] SIEM + Logs Lab

---

**próxima etapa**

Depois de consolidar Cybersecurity, o roadmap avança para **Cloud Security**, conectando os conhecimentos de segurança com AWS, IAM, VPC, Security Groups, CloudTrail e monitoramento.

[← Voltar para o Roadmap](roadmap.md)

[← Fundamentos](fundamentos.md)

[→ Cloud Security](cloud-security.md)

[→ Portfólio](portfolio.md)

---

<div align="center">

<sub>Cybersecurity • Red Team • Blue Team • SOC • Web Security</sub>

</div>
