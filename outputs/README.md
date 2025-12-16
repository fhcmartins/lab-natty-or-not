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


# *Resultado do Prompt 1:*
Uma transportadora rodoviária de cargas no Brasil conseguiu reduzir em 35% o tempo médio de entrega ao combinar automação de processos, IA generativa no atendimento ao cliente e otimização de rotas com machine learning de forma integrada. O resultado foi uma operação mais previsível, com menos retrabalho interno, maior uso inteligente da frota e experiência de cliente muito superior.  

## Ponto de partida: diagnósticos e metas  

Antes da transformação, a empresa operava com processos fortemente manuais: conferência de cargas em planilhas, roteirização feita “no feeling” pelos supervisores e atendimento ao cliente centralizado em poucos analistas sobrecarregados. O lead time médio porta‑a‑porta era de 5 dias em operações B2B regionais, com alto índice de reentregas por endereços incompletos e janelas de recebimento mal gerenciadas.  

A meta definida pela diretoria foi agressiva: reduzir o tempo médio de entrega para algo em torno de 3,2 dias (queda de aproximadamente 35%) em 12 meses, sem aumento proporcional de frota ou quadro de pessoal administrativo. Para isso, o plano foi estruturado em três frentes: automação dos fluxos operacionais, atendimento com IA generativa e roteirização inteligente com machine learning.  

## Automação de processos operacionais  

A primeira onda foi automatizar processos críticos: cadastro de pedidos, emissões de documentos, agendamento de coletas, conferência de carga e disparo de atualizações de status. Sistemas de WMS/TMS integrados passaram a receber pedidos via API diretamente dos ERPs dos clientes, eliminando digitação manual e reduzindo erros de cadastro em mais de 60%.  

Em números práticos, tarefas que consumiam 15 minutos por pedido foram reduzidas para cerca de 3 minutos, somando uma economia de mais de 400 horas/mês em uma operação com 2.000 pedidos mensais. Essa produtividade extra foi redirecionada para o planejamento de janelas de carregamento e monitoramento de exceções, agilizando a saída dos veículos e diminuindo tempos mortos em pátio.  

## IA generativa no atendimento ao cliente  

Na sequência, a empresa implementou um canal de atendimento com IA generativa, semelhante às soluções já adotadas por grandes players de logística para tirar dúvidas, rastrear encomendas e orientar sobre devoluções. Esse assistente, treinado com scripts internos, tabelas de frete e políticas de SLA, passou a responder automaticamente a consultas de status de entrega, segunda via de documentos e orientações de recebimento.  

Com isso, cerca de 75–80% das demandas de primeiro nível foram resolvidas sem intervenção humana, gerando uma queda significativa no volume de ligações e e‑mails. Em termos numéricos, o tempo médio de resposta ao cliente caiu de 2 horas (fila de e‑mail e telefone) para menos de 1 minuto, e o time de atendimento pôde focar nos casos críticos, como atrasos, avarias e remarcações sensíveis. Essa agilidade reduziu o “tempo de decisão” em situações de exceção, encurtando o ciclo entre detectar um problema na rota e tomar uma ação corretiva.  

## Otimização de rotas com machine learning  

A terceira frente foi a adoção de algoritmos de machine learning para roteirização dinâmica, considerando histórico de tráfego, janelas de entrega, perfil dos clientes e características dos veículos. Em vez de rotas fixas, o sistema passou a recalcular diariamente os melhores percursos, buscando equilibrar tempo, custo e capacidade da frota, algo já observado em distribuidoras e transportadoras que obtêm ganhos relevantes com essa abordagem. 

Os modelos, alimentados por dados de GPS, histórico de atrasos e eventos de trânsito, identificaram padrões como corredores com congestionamento recorrente em determinados horários e clientes com maior probabilidade de recusa fora de janelas específicas. Com isso, a quilometragem rodada por entrega caiu cerca de 15% e o tempo médio de trajeto por rota foi reduzido em aproximadamente 25–30%, alinhado a benchmarks de entregas até 30% mais rápidas em operações que utilizam IA para roteirização.  

## Resultado consolidado: 35% menos tempo de entrega  

A combinação das três alavancas gerou um efeito composto. A automação reduziu gargalos internos e atrasos de saída; a IA generativa acelerou decisões e liberou o time para gerir exceções; e a roteirização com machine learning encurtou efetivamente as viagens. Em um horizonte de 9 a 12 meses, o tempo médio de entrega caiu de 5 dias para cerca de 3,2 dias, representando uma redução de aproximadamente 35%, com manutenção da mesma frota e crescimento de volume em torno de 10%.  

Além do ganho direto no lead time, a empresa registrou aumento de satisfação do cliente, queda de custos operacionais em torno de 15–20% e maior previsibilidade na operação, fortalecendo sua competitividade no mercado brasileiro de transporte de cargas. Esses resultados mostram que a combinação pragmática entre automação, IA generativa e machine learning deixa de ser apenas tendência para se tornar um diferencial concreto no dia a dia da logística. 

# *Resultado do Prompt 2*
Gestores de logística, a IA generativa já deixou de ser “futuro” no transporte de cargas – ela está virando vantagem competitiva agora.

👉 1. Menos retrabalho no SAC  
Chatbots treinados com a base de conhecimento da transportadora conseguem responder automaticamente dúvidas repetitivas, gerar segunda via de documentos e registrar reclamações, filtrando apenas os casos complexos para o time humano. Isso reduz retrabalho, filas e desgaste da equipe de atendimento.[web:12][web:59]  

👉 2. Status de entrega em segundos no WhatsApp  
Integrada ao TMS e ao rastreamento, a IA responde em tempo real perguntas como “onde está meu pedido?” ou “qual a previsão de entrega?”, além de enviar notificações proativas em cada etapa da jornada. Resultado: menos ligações, mais transparência e cliente no controle da experiência.[web:45][web:48][web:57]  

👉 3. Decisão mais rápida com resumos inteligentes  
Em vez de navegar por dezenas de relatórios, o gestor faz perguntas em linguagem natural (“como está o meu OTIF nesta semana?”) e recebe resumos automáticos dos indicadores com alertas e recomendações. Assim, a energia do time vai para a ação, não para a coleta e consolidação de dados.[web:12][web:46][web:53]  

Quem conseguir combinar operação sólida com IA generativa aplicada ao dia a dia vai liderar a próxima onda de eficiência logística no Brasil.


