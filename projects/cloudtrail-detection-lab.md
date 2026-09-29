<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:2563eb&height=180&section=header&text=CloudTrail%20Detection%20Lab&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=AWS%20%7C%20CloudTrail%20%7C%20Detection%20%7C%20Investigation&descAlignY=58&descSize=16" width="100%"/>

<div align="center">

**cloudtrail-detection-lab**

<sub>Detecção e investigação de eventos de segurança utilizando AWS CloudTrail.</sub>

</div>

---

**objetivo**

Estudar como eventos de API e atividades administrativas podem ser registrados e utilizados para investigação de segurança em AWS.

---

**conceitos**

- AWS CloudTrail
- API Events
- Audit Logs
- Detection
- Monitoring
- Investigation
- IAM
- Incident Response

---

**fluxo**

```text
Ação na AWS
     ↓
Evento de API
     ↓
CloudTrail
     ↓
Registro
     ↓
Análise
     ↓
Detecção
     ↓
Investigação
```

---

**cenários**

Criar eventos controlados para estudar:

- criação ou alteração de recursos;
- alterações de IAM;
- mudanças de configuração;
- ações administrativas;
- atividades fora do comportamento esperado.

---

**metodologia**

```text
Gerar evento controlado
        ↓
Localizar evento
        ↓
Identificar usuário / serviço
        ↓
Analisar ação
        ↓
Verificar contexto
        ↓
Determinar impacto
        ↓
Documentar
```

---

**evidências**

Registrar:

- evento;
- horário;
- identidade;
- ação;
- recurso;
- origem;
- análise;
- conclusão.

---

**resultado esperado**

Aprender a utilizar registros de CloudTrail como fonte de evidências para monitoramento e investigação.

---

**status**

```text
[ ] Planejamento
[ ] CloudTrail
[ ] Eventos
[ ] Cenários
[ ] Detecção
[ ] Investigação
[ ] Documentação
[ ] Concluído
```

---

**navegação**

[← Projects](README.md)

[→ Supply Chain Security Lab](supply-chain-security-lab.md)

[→ Cloud Security](../docs/cloud-security.md)

[← README principal](../README.md)

---
