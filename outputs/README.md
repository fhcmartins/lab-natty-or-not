## Arquitetura (visão simplificada)

flowchart LR
A[Usuário / Ideia de Conteúdo] --> B[n8n]
B --> C[Modelo de IA de Texto]
C --> D[Texto gerado: Natural ou Fake Natty?]
D --> E[Repositório GitHub (outputs/)]
D --> F[Redes Sociais / Portfólio]


- **n8n** orquestra a chamada aos modelos de IA com base nos prompts deste repositório.  
- Os resultados (textos “Natural ou Fake Natty?”) são salvos em `outputs/` e podem ser publicados nas redes.
