# Fluxo de Telas – MVP do FinChat

Este documento descreve o fluxo de telas do MVP do FinChat, um assistente financeiro pessoal com interface conversacional, protagonizado pelo agente Nino.

---

## 🟢 Tela 1 – Boas-vindas

**Objetivo**: Apresentar o agente Nino e iniciar a jornada do usuário.

**Elementos**:
- Avatar do Nino
- Mensagem de saudação motivacional
- Botão "Começar"

**Exemplo de mensagem**:
Nino: Olá! Que bom te ver por aqui. Pronto para transformar sua relação com o dinheiro? Cada passo conta, e eu tô com você nessa! 🚀
[Começar]

---

## 🟡 Tela 2 – Definição de Meta

**Objetivo**: Permitir que o usuário defina uma meta financeira inicial.

**Elementos**:
- Campo de texto para digitar a meta (ex: "Viajar para Salvador")
- Sugestões rápidas (ex: "Quitar dívidas", "Comprar um celular", "Economizar para emergência")
- Botão "Confirmar"

**Exemplo de interação**:

Nino: Qual é o seu objetivo financeiro neste momento? Pode me contar com suas palavras. 😊
Usuário: Quero juntar dinheiro para viajar.
Nino: Que demais! ✈️ Para onde você quer ir?
Usuário: Salvador.
Nino: Perfeito! Vamos fazer isso acontecer juntos. 💪

---

## 🟠 Tela 3 – Registro de Despesa

**Objetivo**: Registrar uma nova transação de forma rápida e natural.

**Elementos**:
- Campo de texto para digitar ou colar a informação
- Botão de microfone para entrada por voz
- Botão de anexo para enviar comprovante (imagem)
- Sugestões rápidas (ex: "Gastei R$20 no mercado", "Paguei R$50 no Uber")

**Exemplo de interação**:

Usuário: Gastei 30 no Uber.
Nino: Uber é vida, né? 🚗 Já anotei R$30 em Transporte. Quer salvar esse trajeto como favorito?

---

## 🔵 Tela 4 – Confirmação e Categorização

**Objetivo**: Confirmar ou ajustar a categoria da despesa registrada.

**Elementos**:
- Card com resumo da transação
- Sugestão de categoria
- Botões: "Confirmar", "Alterar categoria"

**Exemplo de interação**:

Nino: Padaria da Esquina, R$15. Isso costuma entrar como “Lazer”. Tudo certo ou prefere mudar?
[Confirmar] [Alterar para Alimentação]

---

## 🟣 Tela 5 – Micro-Relatório Semanal

**Objetivo**: Apresentar um resumo visual e motivacional da semana.

**Elementos**:
- Card com gráfico simples (pizza ou barras)
- Destaques positivos
- Frase motivacional
- Botão "Ver detalhes" (opcional)

**Exemplo de interação**:

Nino: Aqui está seu resumo da semana! 🎉

Total gasto: R$450
🥇 Destaque: Alimentação bem controlada!
💡 Dica: Que tal revisar os gastos com transporte?


---

## 🔴 Tela 6 – Sugestão Proativa

**Objetivo**: Engajar o usuário com uma sugestão personalizada.

**Elementos**:
- Mensagem do agente com sugestão
- Botões: "Aceitar", "Talvez depois", "Editar meta"

**Exemplo de interação**:

Nino: Se você guardar R$5 por dia, sua viagem dos sonhos chega 1 semana antes. ✨ Que tal tentar?
[Aceitar] [Talvez depois] [Editar meta]

---

## ⚪ Tela Persistente – Interface de Chat

**Objetivo**: Ser a tela principal do app, onde todas as interações acontecem.

**Elementos**:
- Área de conversa com Nino
- Campo de texto para digitar
- Ícone de microfone 🎤
- Ícone de anexo 📎
- Histórico de interações
- Cards e sugestões inline

**Exemplo de interface**:

Nino: Olá, Marcus! Pronto para começar a cuidar das suas finanças com leveza e inteligência? 😊
[Campo de texto] [🎤] [📎]

---

## 🔚 Considerações Finais

- Todas as telas devem manter consistência visual e emocional com a persona do Nino.  
- O fluxo deve ser fluido, sem transições bruscas ou sobrecarga de informações.  
- O usuário nunca deve sentir que está sendo avaliado — apenas acompanhado.
