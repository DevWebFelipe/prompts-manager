# Prompts Manager

> Projeto desenvolvido com foco na utilização da IA dentro do VSCode, fazendo uso da integração com o Figma através do MCP para otimizar o fluxo entre design e código.

---

## 🧩 Visão geral

O **Prompts Manager** foi criado como um **laboratório prático** para explorar o uso da inteligência artificial no processo de desenvolvimento, especialmente dentro do **VSCode**, utilizando **integração com o Figma via MCP** como base para geração de prompts e conteúdo fiel ao design.

A ideia central do projeto é **usar a IA como uma ferramenta de apoio** — não como substituta — para:

- Aumentar a produtividade no desenvolvimento;
- Reduzir o tempo gasto em tarefas repetitivas;
- Gerar código e conteúdo com base em designs reais;
- Manter a **clareza, entendimento e qualidade** do código por meio de **revisão e refatoração manual**.

---

## 💡 Como o projeto foi construído

Durante o desenvolvimento, foi utilizada a **integração do Figma com o VSCode via MCP**, permitindo:

- **Extração automática de variáveis de cor** e tokens diretamente do design;
- **Uso de links de partes específicas do layout no Figma** para gerar prompts precisos;
- **Geração de conteúdo e código com fidelidade ao design**, utilizando a IA como apoio.

Após a geração, o foco do projeto esteve em **revisar, refatorar e melhorar** todo o código produzido, garantindo qualidade e aprendizado sobre o funcionamento da IA no fluxo de trabalho.

---

## 🎯 Objetivo principal

Este projeto foi criado com o **objetivo de aprender a utilizar a IA como um auxílio real no dia a dia de desenvolvimento**, explorando:

- **Revisão e conferência** do código gerado;
- **Refatoração e melhorias** orientadas por boas práticas;
- **Entendimento do comportamento da IA** e como guiar suas respostas por meio de prompts bem estruturados.

O resultado é um exemplo prático de como equilibrar **produtividade** e **controle humano** dentro do processo de desenvolvimento assistido por IA.

---

## 📂 Estrutura do projeto

```
/
├── .vscode/             ← configurações locais do VSCode
├── assets/              ← imagens, ícones e recursos estáticos
├── index.html           ← exemplo ou protótipo principal
├── style.css            ← estilos do projeto
├── script.js            ← lógica e integração com IA / prompts
└── README.md            ← este arquivo de documentação
```

---

## ⚙️ Fluxo de uso

| Etapa                    | Descrição                                                       |
| ------------------------ | --------------------------------------------------------------- |
| 1️⃣ Extração de variáveis | Obtenção das cores e tokens do Figma via integração MCP         |
| 2️⃣ Criação de prompts    | Geração de prompts a partir de links ou trechos do design       |
| 3️⃣ Geração com IA        | IA cria código ou conteúdo baseado no design                    |
| 4️⃣ Revisão manual        | Refatoração, conferência e melhoria do código gerado            |
| 5️⃣ Aprendizado           | Ajuste dos prompts e entendimento dos padrões de resposta da IA |

---

## 🚀 Como executar localmente

> Este projeto é um **protótipo de aprendizado**, portanto não possui dependências complexas. Você pode adaptá-lo conforme seu ambiente e ferramentas.

1. Clone o repositório:

   ```bash
   git clone https://github.com/DevWebFelipe/prompts-manager.git
   cd prompts-manager
   ```

2. (Opcional) Instale dependências, caso utilize Node.js ou pacotes auxiliares:

   ```bash
   npm install
   ```

3. Configure suas chaves de API (Figma, MCP, IA) se necessário.

4. Execute localmente:

   ```bash
   npm start
   ```

   ou simplesmente abra o `index.html` no navegador.

---

## 🛠 Tecnologias e ferramentas envolvidas

- **VSCode** — ambiente principal de desenvolvimento
- **Figma + MCP** — integração usada para extrair dados e gerar prompts
- **IA (ChatGPT / GPT)** — geração de código e conteúdo assistido
- **HTML, CSS e JavaScript** — base do projeto e exemplos práticos

---

## ✅ Boas práticas aplicadas

- **Revisar sempre** o código gerado pela IA
- **Refatorar e melhorar** antes de integrar
- **Compreender o resultado**, não apenas aceitá-lo
- **Usar a IA como assistente**, mantendo o controle humano
- **Documentar e ajustar** os prompts conforme a necessidade

---

## 🧠 Aprendizados

O projeto demonstrou que **a IA pode ser uma aliada poderosa** quando usada com propósito e entendimento.  
Entre os principais aprendizados estão:

- A importância de **prompts claros e contextuais**;
- Como **guiar a IA** para gerar resultados próximos do esperado;
- A necessidade constante de **revisão e refino manual**;
- O ganho de **tempo e produtividade**, mantendo o **domínio técnico** do código.

---

## 📈 Próximos passos

- Criar uma interface visual para gerenciar prompts
- Armazenar histórico de resultados e versões
- Ampliar suporte a outras ferramentas de design
- Automatizar testes no código gerado
- Criar extensão própria no VSCode

---

## 📜 Licença

MIT License  
Copyright (c) 2025  
[DevWebFelipe](https://github.com/DevWebFelipe)
