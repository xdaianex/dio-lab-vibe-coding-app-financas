# 💸 App Minhas Finanças

Esse projeto foi desenvolvido como Desafio de Projeto da DIO sobre Vibe Coding utilizando o Lovable e o Copilot Web. A proposta doi criar um aplicativo de organização financeira pessoal baseado em interações em linguagem natural.

PRD refinado no Copilot Web:
```markdown
# PRD Revisado – Aplicativo de Organização de Finanças Pessoais

## Contexto
Quero criar um aplicativo de Organização de Finanças Pessoais que funcione por meio de conversas com o usuário em linguagem natural.  
A ideia é facilitar o controle financeiro de forma simples e natural, sem formulários manuais ou planilhas complexas.  
Também deve possibilitar a visão dos gastos e economias por meio de gráficos.  
Visão futura: integração com bancos e carteiras digitais para automatizar ainda mais o registro de transações.

## Problema
Muitas pessoas desistem de controlar seus gastos porque os apps atuais exigem muita entrada manual e pouca personalização.  
Além disso, há falta de feedback prático e educativo que ajude o usuário a melhorar seus hábitos financeiros.  
Quero resolver isso com uma experiência de conversa e recomendações automáticas de economia.

## Público-Alvo
Pessoas que querem começar a organizar suas finanças de forma prática e sem complicação, principalmente iniciantes.  
Perfil sugerido: jovens adultos, profissionais em início de carreira e pessoas que nunca usaram apps financeiros.

## Funcionalidades-Chave
1. Registrar gastos via chat em linguagem natural  
   - Ex.: “gastei 50 reais no mercado”  
   - Reconhecimento automático de valores, categorias e datas  
2. Classificação automática das transações  
   - Algoritmo simples de NLP + regras iniciais  
   - Possibilidade de correção manual pelo usuário  
3. Definir e acompanhar metas financeiras  
   - Ex.: economizar R$500/mês  
   - Alertas amigáveis sobre progresso  
4. Agente Financeiro Educativo  
   - Recomendações curtas e práticas (“reduza gastos com delivery em 10%”)  
   - Tom acessível, sem jargão técnico  
5. Relatórios personalizados e gráficos simples  
   - Pizza (categorias), linha (evolução mensal), barra (comparação metas)  
   - Exportação opcional em PDF ou imagem  
6. Sugestões de investimentos básicos  
   - Orientações iniciais sobre produtos financeiros acessíveis e de baixo risco  
   - Linguagem simples para iniciantes  

## Entregável da IA (MVP)
Plano sugerido:

| Etapa | Entregável | Objetivo |
|-------|------------|----------|
| 1. Protótipo Conversacional | Fluxo de chat com exemplos de entradas e respostas | Validar usabilidade da linguagem natural |
| 2. Classificação Automática | Regras básicas de categorização (alimentação, transporte, lazer) | Testar precisão inicial |
| 3. Metas Financeiras | Tela simples para definir e acompanhar metas | Avaliar engajamento |
| 4. Relatórios Gráficos | Dashboard com 2–3 tipos de gráficos | Validar clareza visual |
| 5. Feedback do Agente | Recomendações automáticas baseadas em padrões de gasto | Medir percepção de valor |
| 6. Sugestões de Investimentos | Conteúdo educativo sobre opções seguras | Avaliar interesse do público |

## Validação Inicial
- Teste com 20–30 usuários iniciantes  
- Métricas principais:  
  - Facilidade de uso (NPS ou pesquisa rápida)  
  - Frequência de registro de gastos  
  - Clareza dos relatórios  
  - Utilidade percebida das dicas e sugestões de investimento  

## Sugestões de Investimentos (para iniciantes)
O aplicativo pode oferecer recomendações simples e educativas, como:  
- Tesouro Direto (Tesouro Selic): investimento seguro e acessível, ideal para reserva de emergência  
- CDBs de bancos confiáveis: rendem mais que a poupança e têm cobertura do FGC  
- Fundos de investimento conservadores: permitem diversificação sem exigir conhecimento avançado  
- Caixinhas de investimento (em fintechs): práticos para metas de curto prazo  
- ETFs básicos: para quem deseja começar a investir em renda variável de forma simples e diversificada  

Essas sugestões devem ser apresentadas em tom educativo, sem jargão técnico, sempre reforçando que o usuário deve avaliar seu perfil de risco e buscar orientação profissional quando necessário.
```

Interações com o Lovable:
> Crie um App de Finanças Pessoais com base no seguinte PRD (Product Requirements Document):{PRD}

> Qualquer coisa que escrevo no chat do assistente financeiro retorna a mesma mensagem dizendo que registrou o gasto, mesmo quando o que eu escrevo não é gasto. Poderia corrigir?

> O "assistente financeiro" deve alterar o valor dos gastos, economia e saldo de acordo com as informações que eu digite no chat.

Resultado final no Loveble: https://meu-coach-dinheiro.lovable.app/ (não carrega!)

<img width="1916" height="892" alt="image" src="https://github.com/user-attachments/assets/224a7a80-8089-4651-b9ec-6611806b20ee" />

# Minhas Finanças – Aplicativo de Organização Financeira com IA

## Objetivo

“Minhas Finanças” é um aplicativo web voltado para o gerenciamento de finanças pessoais por meio de conversas em linguagem natural com um agente inteligente. Ele busca simplificar o controle financeiro, tornando a experiência mais intuitiva e acessível para iniciantes.

## Principais Funcionalidades

- **Chat Financeiro Inteligente**  
  Interface central baseada em conversas, onde o usuário pode registrar transações como “Recebi 3300 reais hoje” ou “Gastei no mercado”, e o agente interpreta e organiza essas informações automaticamente.

- **Classificação de Gastos**  
  Painel lateral com categorias pré-definidas como alimentação, transporte, saúde, lazer e compras, facilitando a organização dos registros.

- **Metas Financeiras**  
  Painel de metas com objetivos como “Reserva de Emergência” e “Viagem nas Férias”, acompanhados de barras de progresso que mostram o avanço do usuário em cada meta.

- **Publicação e Integração**  
  Opções para publicar o chatbot em domínio próprio, incorporá-lo em

## Reflexão

### O que funcionou bem?
Nada! rs Mas aprendi muito, sou de outra área e tudo é novidade para mim.

### O que não funcionou como o esperado?
Já na primeira etapa que era o refinamento do PRD no Copilot Web, mesmo com todo meu esforço rs, não ficou bom o suficiente para ser corrigido com o limite de interações no Lovable, continuou com problemas...

### O que aprendeu sobre conversar com IAs?
Aprendi que não precisa ser especialista para fazer bom uso. Como utiliza linguagem natural, só precisamos ser claros no que solicitamos, oferecer contexto adequado entre outras coisas. Até programar é possível!

## 💬 Conclusão
Este curso e, especialmente, este desafio acrescentaram muito no meu aprendizado e despertaram o meu interesse em aprender ainda mais.

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
