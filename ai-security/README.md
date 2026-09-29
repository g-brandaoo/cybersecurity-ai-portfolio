<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:2563eb&height=180&section=header&text=AI%20Security&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=LLM%20Security%20%7C%20AI%20Safety%20%7C%20Defense&descAlignY=58&descSize=16" width="100%"/>

<div align="center">

**ai-security**

<sub>Segurança de aplicações de IA, LLMs, dados e sistemas inteligentes.</sub>

</div>

---

**sobre**

Esta pasta reúne os fundamentos e estudos relacionados à segurança de sistemas de inteligência artificial.

O objetivo é compreender como aplicações de IA podem ser atacadas, quais riscos surgem durante seu desenvolvimento e como implementar mecanismos de proteção.

---

**objetivo**

Desenvolver conhecimentos práticos em:

- Segurança de LLMs
- Prompt Injection
- RAG Security
- Segurança de APIs
- Proteção de dados
- Controle de acesso
- Segurança de ferramentas
- Validação de entradas e saídas
- AI Supply Chain Security
- Monitoramento
- AI-powered Defense

---

**fundamentos**

Antes de estudar ataques específicos, é importante compreender:

- funcionamento de LLMs;
- tokens;
- prompts;
- contexto;
- embeddings;
- RAG;
- APIs;
- ferramentas externas;
- agentes;
- controle de acesso;
- armazenamento de dados;
- logs e monitoramento.

---

**principais riscos**

**Prompt Injection**

Manipulação das instruções fornecidas ao modelo para alterar seu comportamento.

**Data Leakage**

Exposição indevida de informações sensíveis através da aplicação de IA.

**RAG Security**

Riscos relacionados à recuperação, armazenamento e utilização de documentos externos.

**Tool Security**

Riscos causados quando um modelo possui acesso a ferramentas, APIs ou sistemas externos.

**Output Manipulation**

Saídas manipuladas ou inesperadas que podem afetar sistemas que confiam diretamente na resposta do modelo.

**AI Supply Chain**

Riscos relacionados a modelos, datasets, bibliotecas, dependências e serviços utilizados pela aplicação.

---

**arquitetura segura**

```text
Usuário
   ↓
Validação de entrada
   ↓
Aplicação
   ↓
Controle de acesso
   ↓
LLM
   ↓
Validação da saída
   ↓
Ferramentas autorizadas
   ↓
Sistema externo
   ↓
Logs e monitoramento
