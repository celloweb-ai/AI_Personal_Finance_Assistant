# Contexto
Quero criar um aplicativo de Organização de Finanças Pessoais que funcione por meio de conversas com o usuário.  
A ideia é facilitar o controle financeiro de forma simples e natural, sem formulários manuais ou planilhas complexas.

# Problema
Muitas pessoas desistem de controlar seus gastos porque os apps atuais exigem muita entrada manual e pouca personalização.  
Quero resolver isso com uma experiência de conversa e recomendações automáticas de economia.

# Público-Alvo
Pessoas que querem começar a organizar suas finanças de forma prática e sem complicação, principalmente iniciantes.

# Funcionalidades-Chave
1. Registrar gastos via chat em linguagem natural.  
2. Classificar automaticamente as transações.  
3. Definir e acompanhar metas financeiras.  
4. Receber dicas de economia do “Agente Financeiro”.  
5. Visualizar relatórios simples e personalizados.

# Entregável da IA
Gerar um plano de MVP com as principais telas, recursos necessários e um esboço de validação inicial.  
Usar tom educativo e linguagem acessível, em português.

# Prompt Final 👇

# MISSÃO
Você é o Tech Lead e Product Designer de uma startup. Sua missão é estruturar o conceito do "FinChat" (nome provisório), um assistente financeiro pessoal baseado inteiramente em interfaces conversacionais (CUI - Conversational User Interface).

# MANIFESTO DO PRODUTO (A "VIBE")
Nós acreditamos que controlar finanças não deve ser chato. Nosso app não é uma calculadora, é um companheiro financeiro. Ele deve ser:
- **Invisível:** O máximo de automação possível.
- **Empático:** Nunca julga os gastos do usuário, apenas orienta.
- **Simples:** Se parece com uma planilha, nós falhamos.

# DETALHAMENTO DAS FUNCIONALIDADES
Para cada funcionalidade abaixo, eu preciso que você defina *como* ela funciona no back-end conceitual e dê um exemplo de interação no front-end (chat):

1.  **Input Multimodal:** Aceitar texto ("gastei 30 no uber"), voz (áudio transcrito) e idealmente leitura de comprovantes (imagens).
2.  **Categorização Contextual:** O agente deve aprender com o usuário. Se ele sempre classifica "Padaria da Esquina" como "Lazer" (e não alimentação), o agente deve se adaptar.
3.  **Feedback Loop (Agente Proativo):** O agente não espera o usuário perguntar. Ele deve analisar padrões e sugerir ações: "Parece que se você economizar R$5 por dia, atinge sua meta de viagem 1 semana antes. Topa tentar?".
4.  **Micro-Relatórios:** Cards visuais simples dentro do chat que resumem a semana, sem precisar sair da tela de conversa.

# RESTRIÇÕES DO MVP
- Deve ser mobile-first.
- Foco total na rapidez de inserção (o usuário deve gastar menos de 5 segundos para registrar algo).

# O QUE VOCÊ DEVE ENTREGAR
1.  **Persona do Agente:** Defina o nome, tom de voz e 3 regras de comportamento do nosso assistente IA.
2.  **Jornada do Usuário (Dia 1):** Descreva passo a passo a primeira interação de um novo usuário com o app.
3.  **Stack Tecnológica Sugerida:** Que ferramentas de IA e frameworks (ex: React Native, OpenAI API, etc.) você recomenda para este MVP e por quê?
4.  **Plano de Validação de Hipótese:** Como vamos medir se as pessoas realmente preferem conversar a usar formulários? Defina 1 métrica principal (North Star Metric).
