# Laboratório de Voz e Linguagem com Microsoft Azure

Este repositório faz parte do desafio proposto pela DIO, com foco em praticar e aprofundar o uso das ferramentas **Azure Speech Studio** e **Language Studio**. O objetivo foi explorar na prática soluções de inteligência artificial aplicadas à fala e à linguagem natural, documentando os conhecimentos adquiridos durante a experiência.

---

## 🧠 Tecnologias Utilizadas

- [Microsoft Azure Language Studio](https://language.azure.com/)
- [Microsoft Azure Speech Studio](https://speech.azure.com/)
- Azure Bot Service

---

## 🔍 Funcionalidades e Conceitos Explorados

### 1. **Language Studio**

O Language Studio é uma plataforma baseada em interface gráfica que permite analisar e processar linguagem natural com diversos recursos:

- **Detecção de idioma predominante**;
- **Análise de sentimentos**;
- **Extração de frases-chave**;
- **Identificação de entidades nominais e personalizadas**.

Essas funcionalidades ajudam a classificar e entender melhor os dados textuais, permitindo extrair métricas e interpretações semânticas úteis para várias aplicações.

---

### 2. **Serviço de Bot do Azure**

O Azure Bot Service permite criar agentes conversacionais que interagem com usuários via chat, e-mail, ligação, SAC, entre outros canais. Seu funcionamento depende diretamente da base de dados conectada e da qualidade das intenções e entidades mapeadas. Quanto mais rica for sua base de conhecimento, mais eficaz será a resposta do bot.

O bot utiliza:

- **Palavras-chave e intenções** para identificar dúvidas do usuário;
- **Consultas em bases estruturadas** para fornecer as respostas corretas.

---

### 3. **Compreensão de Linguagem Coloquial (LUIS)**

Na linguagem natural, especialmente a coloquial, as frases nem sempre seguem estruturas formais. A compreensão dessa linguagem depende de três componentes principais:

- **Declaração (Utterance)**: O que o usuário diz, ex: "Acenda a luz".
- **Entidade (Entity)**: O objeto ou dado mencionado, ex: "luz".
- **Intenção (Intent)**: A ação que o usuário deseja realizar, ex: "acender".

Esses elementos são essenciais para que o bot entenda comandos do dia a dia, mesmo com variações de linguagem.

---

### 4. **Reconhecimento e Síntese de Fala**

O Azure Speech Studio oferece recursos como:

- **Reconhecimento de fala**: converte áudio em texto de forma automática.
- **Síntese de fala (Text-to-Speech)**: transforma texto escrito em fala audível.

Essas ferramentas têm aplicações práticas em acessibilidade (por exemplo, para pessoas com deficiência visual), automação de atendimentos e dispositivos interativos.

---

### 5. **Speech Studio**

O Speech Studio centraliza os recursos de fala e oferece uma interface para:

- Gerar transcrições de áudios;
- Criar vozes sintéticas personalizadas;
- Integrar reconhecimento de fala com outros serviços da Microsoft.

---

## 📝 Considerações Finais

Este laboratório foi essencial para compreender como a inteligência artificial pode ser aplicada de forma prática à linguagem e à fala. O uso do Azure Speech Studio e Language Studio permite construir soluções que interpretam, analisam e interagem com o ser humano de forma cada vez mais natural.

Durante o desafio, aprendi a:

- Configurar e explorar os recursos de linguagem e fala;
- Integrar análise semântica e intenção em projetos práticos;
- Utilizar interfaces amigáveis da Microsoft para treinar e testar modelos de IA.

---
