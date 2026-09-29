<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:2563eb&height=180&section=header&text=IAM%20Security%20Lab&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=IAM%20%7C%20Identity%20%7C%20Least%20Privilege&descAlignY=58&descSize=16" width="100%"/>

<div align="center">

**iam-security-lab**

<sub>Laboratório de identidade, autenticação, autorização e controle de acesso.</sub>

</div>

---

**objetivo**

Estudar como identidades e permissões podem ser organizadas de forma segura em ambientes Cloud.

---

**conceitos**

- IAM
- Identidade
- Autenticação
- Autorização
- Policies
- Roles
- Groups
- Least Privilege
- Access Control
- Credential Security

---

**modelo**

```text
Identidade
    ↓
Autenticação
    ↓
Autorização
    ↓
Policy
    ↓
Recurso
```

---

**etapas**

**01 — Identidades**

Criar identidades de laboratório e definir suas funções.

**02 — Permissões**

Criar políticas específicas para cada necessidade.

**03 — Menor privilégio**

Reduzir permissões desnecessárias.

**04 — Validação**

Verificar quais ações cada identidade consegue realizar.

**05 — Auditoria**

Revisar permissões e identificar acessos excessivos.

---

**cenários**

Exemplos:

- usuário somente leitura;
- usuário administrativo;
- acesso a recurso específico;
- função para serviço;
- política excessivamente permissiva para análise e correção.

---

**evidências**

- políticas;
- grupos;
- roles;
- testes de acesso;
- comparação de permissões;
- alterações realizadas;
- conclusões.

---

**resultado esperado**

Compreender como controlar o acesso aos recursos e aplicar o princípio do menor privilégio.

---

**status**

```text
[ ] Planejamento
[ ] Identidades
[ ] Policies
[ ] Roles
[ ] Least Privilege
[ ] Testes
[ ] Auditoria
[ ] Documentação
[ ] Concluído
```

---

**navegação**

[← Projects](README.md)

[→ CloudTrail Detection Lab](cloudtrail-detection-lab.md)

[→ Cloud Security](../docs/cloud-security.md)

[← README principal](../README.md)

---
