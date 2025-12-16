# Natural ou Fake Natty? – IA aplicada à logística

Este repositório é meu projeto do lab **“Natural ou Fake Natty? Como Vencer na Era das IAs Generativas!”** da DIO, adaptado para o contexto de logística, transporte de cargas e automação com IA generativa.

## Arquitetura (visão simplificada)

flowchart LR
A[Usuário / Ideia de Conteúdo] --> B[n8n]
B --> C[Modelo de IA de Texto]
C --> D[Texto gerado: Natural ou Fake Natty?]
D --> E[Repositório GitHub (outputs/)]
D --> F[Redes Sociais / Portfólio]

- **n8n** orquestra a chamada aos modelos de IA com base nos prompts deste repositório.  
- Os resultados (textos “Natural ou Fake Natty?”) são salvos em `outputs/` e podem ser publicados nas redes.

## Conteúdos deste lab

- `prompts/` – prompts usados para gerar textos e outros conteúdos.
- `outputs/` – exemplos de textos gerados (Fake Natty) e, futuramente, conteúdos reais (Natural) para comparação.
- `n8n-workflows/` – exports de workflows usados para automatizar a geração de conteúdo.
