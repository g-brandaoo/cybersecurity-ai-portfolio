<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:2563eb&height=180&section=header&text=Cloud%20Security%20Lab&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=AWS%20%7C%20Cloud%20Security%20%7C%20Hardening&descAlignY=58&descSize=16" width="100%"/>

<div align="center">

**cloud-security-lab**

<sub>Laboratório de segurança em ambientes de nuvem com foco em AWS.</sub>

</div>

---

**objetivo**

Aplicar conceitos de segurança em Cloud, utilizando recursos controlados para estudar identidade, rede, armazenamento, monitoramento e proteção de recursos.

---

**conceitos**

- Cloud Security
- AWS
- IAM
- EC2
- S3
- VPC
- Security Groups
- CloudTrail
- CloudWatch
- Hardening
- Least Privilege

---

**arquitetura**

```text
AWS
├── IAM
├── VPC
│   ├── Subnets
│   └── Security Groups
├── EC2
├── S3
└── Monitoring
    ├── CloudTrail
    └── CloudWatch
```

---

**etapas**

**01 — Identidade**

Criar usuários, grupos, funções e permissões seguindo o princípio do menor privilégio.

**02 — Rede**

Configurar uma rede controlada e revisar as regras de acesso.

**03 — Recursos**

Criar recursos de laboratório e analisar suas configurações.

**04 — Monitoramento**

Registrar e analisar eventos relacionados à infraestrutura.

**05 — Hardening**

Identificar configurações desnecessárias ou excessivamente permissivas.

**06 — Validação**

Testar se os controles implementados funcionam conforme esperado.

---

**evidências**

- arquitetura;
- políticas IAM;
- configurações de rede;
- regras de acesso;
- logs;
- eventos;
- alterações de segurança;
- resultados dos testes.

---

**resultado esperado**

Demonstrar compreensão dos principais componentes de uma arquitetura segura em AWS.

---

**status**

```text
[ ] Planejamento
[ ] IAM
[ ] VPC
[ ] Security Groups
[ ] EC2
[ ] S3
[ ] Monitoring
[ ] Hardening
[ ] Documentação
[ ] Concluído
```

---

**navegação**

[← Projects](README.md)

[→ IAM Security Lab](iam-security-lab.md)

[→ Cloud Security](../docs/cloud-security.md)

[← README principal](../README.md)

---
