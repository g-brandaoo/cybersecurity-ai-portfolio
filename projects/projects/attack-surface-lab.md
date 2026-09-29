<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:2563eb&height=180&section=header&text=Attack%20Surface%20Lab&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Attack%20Surface%20%7C%20Asset%20Discovery%20%7C%20Risk%20Analysis&descAlignY=58&descSize=16" width="100%"/>

<div align="center">

**attack-surface-lab**

<sub>Laboratório para identificação, organização e análise de uma superfície de ataque.</sub>

</div>

---

**objetivo**

Desenvolver uma visão prática sobre **Attack Surface**, identificando ativos, serviços, pontos de entrada e possíveis riscos de um ambiente controlado.

O laboratório busca responder:

```text
Quais ativos existem?
       ↓
Quais serviços estão expostos?
       ↓
Quais pontos de entrada existem?
       ↓
Quais riscos estão associados?
       ↓
Como reduzir a superfície de ataque?
```

---

**conceitos**

- Attack Surface
- Assets
- Serviços
- Portas
- Protocolos
- Exposição
- Vulnerabilidades
- Risco
- Hardening
- Attack Surface Management

---

**ambiente**

O laboratório deve utilizar somente **ambientes próprios ou explicitamente autorizados**.

Exemplo:

```text
Máquina de análise
       ↓
Rede de laboratório
       ↓
Máquina(s) alvo controladas
       ↓
Serviços configurados
```

---

**etapas**

**01 — Inventário**

Identificar os ativos existentes no ambiente.

Exemplos:

- máquinas;
- sistemas operacionais;
- servidores;
- aplicações;
- serviços;
- interfaces de rede.

**02 — Descoberta**

Mapear os serviços disponíveis no laboratório.

Registrar:

- endereço;
- porta;
- protocolo;
- serviço;
- versão, quando disponível;
- finalidade.

**03 — Análise**

Avaliar quais componentes representam pontos de exposição.

Perguntas:

- O serviço é necessário?
- Ele precisa estar acessível?
- Existe autenticação?
- Existem controles de acesso?
- O serviço está atualizado?
- Há configuração desnecessária?

**04 — Classificação**

Organizar os pontos encontrados por nível de exposição e relevância para o ambiente.

**05 — Mitigação**

Identificar formas de reduzir a superfície de ataque.

Exemplos:

- remover serviços desnecessários;
- restringir acesso;
- aplicar autenticação;
- atualizar componentes;
- segmentar a rede;
- revisar permissões.

**06 — Validação**

Repetir a análise depois das alterações e comparar os resultados.

---

**registro**

Exemplo de tabela:

| Ativo | Serviço | Porta | Exposição | Risco | Mitigação |
|---|---|---:|---|---|---|
| Servidor A | HTTP | 80 | Rede local | A analisar | Restringir acesso |
| Servidor A | SSH | 22 | Rede local | A analisar | Revisar acesso |
| Servidor B | DNS | 53 | Rede local | A analisar | Validar configuração |

Os valores devem ser preenchidos com os resultados reais do laboratório.

---

**evidências**

Registrar:

- diagrama do ambiente;
- inventário de ativos;
- resultados das descobertas;
- serviços identificados;
- análise dos riscos;
- alterações realizadas;
- comparação antes/depois;
- conclusões.

---

**resultado esperado**

Ao final do laboratório, deve ser possível explicar:

```text
O que compõe a superfície de ataque?
        ↓
Quais pontos estão expostos?
        ↓
Por que estão expostos?
        ↓
Qual é o impacto potencial?
        ↓
Quais controles podem reduzir a exposição?
```

---

**aprendizados**

O laboratório deve consolidar conhecimentos sobre:

- redes;
- serviços;
- protocolos;
- sistemas operacionais;
- vulnerabilidades;
- gerenciamento de riscos;
- hardening;
- segurança defensiva.

---

**próximos passos**

Depois deste laboratório:

- aprofundar Web Security;
- estudar vulnerabilidades;
- construir o Web Vulnerability Lab;
- relacionar Attack Surface com Cloud Security;
- estudar monitoramento e detecção.

---

**status**

```text
[ ] Planejamento
[ ] Ambiente
[ ] Inventário
[ ] Descoberta
[ ] Análise
[ ] Mitigação
[ ] Validação
[ ] Documentação
[ ] Concluído
```

---

**navegação**

[← Voltar para Projects](README.md)

[→ Web Vulnerability Lab](web-vulnerability-lab.md)

[→ Cybersecurity](../docs/cybersecurity.md)

[← README principal](../README.md)

---
