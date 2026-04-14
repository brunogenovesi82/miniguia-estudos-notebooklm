Projeto: Segundo Cérebro - Estratégias de Trading de Larry Williams (MME9)

1. Contexto e Objetivos
Este projeto foca na sistematização das estratégias de seguimento de tendência e reversão desenvolvidas por Larry Williams, centradas na Média Móvel Exponencial de 9 períodos (MME9)
  O objetivo é criar um guia técnico operacional que elimine o viés emocional, utilizando a objetividade matemática para identificar zonas de valor e pontos de exaustão do mercado

Objetivos de Estudo:
  Dominar a identificação dos setups 9.1, 9.2 e 9.3 em diferentes prazos gráficos
  Compreender a matemática por trás da MME9 e sua função como linha de tendência dinâmica
  Implementar protocolos rigorosos de gestão de risco e dimensionamento de posição

2. Curadoria de Fontes
Para alimentar este estudo no NotebookLM, foram selecionadas as seguintes fontes base:
  Análise Técnica de Alta Precisão (PDF): Estudo detalhado sobre a mecânica e psicologia dos setups 9.2 e 9.3
  Backtesting Strategy 9.1 (Artigo): Análise de desempenho histórico do setup 9.1 em índices como NASDAQ e IBOV
  Larry Williams' Strategy (InstaForex): Visão geral sobre ciclos de mercado e padrões como Smash Days
  Proper Money Management (Relatório): Foco na estratégia de gestão de risco que gerou os recordes de Williams
  Transcrições Técnicas (Vídeos): Explicações dinâmicas de especialistas como Fabricio Lorenz, Nelogica e Palex sobre a identificação de "Candles de Referência"

3. Engenharia de Prompts e "Cicatrizes" (Troubleshooting)
Durante o desenvolvimento, as seguintes interações com a IA foram fundamentais:
  Pergunta Estratégica: "Como identificar o setup 9.2?"
  Variação Testada: "Explique o 9.2 focando na diferença entre máxima do candle e fechamento mais alto."
  Aprendizado: A IA inicialmente pode confundir o gatilho com a máxima do candle de sinal. A correção exigiu enfatizar que o 9.2 exige um fechamento abaixo da mínima do anterior, enquanto o 9.3 foca no fechamento em relação ao candle de referência
  Troubleshooting: Foi identificado que a inclinação da MME9 é o filtro absoluto. Se o setup for armado mas a média "vire" contra a posição antes do acionamento, a ordem deve ser cancelada imediatamente

4. Miniguia de Estudo (Entrega Final)
  Resumo Estruturado dos Setups
    Setup 9.1 (Reversão): Identificado pela virada da MME9. Se a média aponta para baixo e vira para cima, marca-se a máxima do candle que produziu a virada para compra
    Setup 9.2 (Correção Curta): Em tendência de alta (MME9 para cima), ocorre quando um candle fecha abaixo da mínima do candle anterior. A entrada é na superação da máxima deste candle de sinal
    Setup 9.3 (Correção Profunda): Exige dois fechamentos consecutivos abaixo do fechamento do "Candle de Referência" (o maior fechamento do rali), sem que a MME9 vire para baixo

Glossário de Conceitos Chave
  Candle de Referência: O candle com o maior fechamento (na compra) ou menor fechamento (na venda) de uma perna de tendência
  Gatilho (Trigger): Ponto exato (geralmente 1 tick acima/abaixo do candle de sinal) onde a operação é acionada
  MME9 (Média Móvel Exponencial): Média que atribui maior peso aos dados recentes, atuando como rastreador de momentum
  Stop Técnico: Posicionamento de saída de emergência abaixo da mínima da correção (na compra) para proteger o capital
  Payoff: Relação entre a média de lucro das operações ganhas versus a média de perda das operações perdedoras; vital para setups com taxa de acerto de 30-40%

Prompts Reutilizáveis para Revisão
  "Analise este gráfico de [Ativo] e identifique se há um Candle de Referência para o setup 9.3 de venda conforme as regras de Larry Williams."
  "Explique o protocolo de 'deslocamento de gatilho' quando o setup 9.2 é armado mas não acionado no candle seguinte."
  "Calcule o dimensionamento de posição para uma conta de R$ 10.000 com risco de 1% e um stop técnico de 50 pontos."
.
