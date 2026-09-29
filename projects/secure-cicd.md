<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:2563eb&height=180&section=header&text=Secure%20CI%2FCD&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=DevSecOps%20%7C%20CI%2FCD%20%7C%20Security%20Automation&descAlignY=58&descSize=16" width="100%"/>

<div align="center">

**secure-cicd**

<sub>Aplicação de controles de segurança em pipelines de desenvolvimento.</sub>

</div>

---

**objetivo**

Estudar como incorporar segurança ao ciclo de desenvolvimento sem depender exclusivamente de verificações manuais no final do processo.

---

**conceitos**

- DevSecOps
- CI/CD
- Secure Coding
- SAST
- Dependency Scanning
- Secret Scanning
- Tests
- Security Gates
- Automation

---

**pipeline**

```text
Commit
  ↓
Build
  ↓
Testes
  ↓
Security Checks
  ↓
Análise
  ↓
Security Gate
  ↓
Deploy
```

---

**controles**

O pipeline pode incorporar:

- testes automatizados;
- análise estática;
- verificação de dependências;
- detecção de secrets;
- validações de configuração;
- controles antes do deploy.

---

**metodologia**

**01 — Código**

Criar uma aplicação simples de laboratório.

**02 — Pipeline**

Configurar o processo automatizado.

**03 — Segurança**

Adicionar verificações de segurança.

**04 — Falha controlada**

Introduzir problemas em ambiente próprio para verificar se os controles detectam o problema.

**05 — Correção**

Corrigir o problema e executar novamente o pipeline.

---

**evidências**

- workflow;
- resultados dos testes;
- alertas;
- falhas;
- correções;
- histórico do pipeline;
- documentação.

---

**resultado esperado**

Demonstrar como práticas de segurança podem fazer parte do desenvolvimento desde as primeiras etapas.

---

**status**

```text
[ ] Planejamento
[ ] Código
[ ] CI
[ ] Testes
[ ] Security Checks
[ ] Security Gate
[ ] Correção
[ ] Documentação
[ ] Concluído
```

---

**navegação**

[← Projects](README.md)

[→ LLM Security Lab](llm-security-lab.md)

[→ Supply Chain Security Lab](supply-chain-security-lab.md)

[← README principal](../README.md)

---
