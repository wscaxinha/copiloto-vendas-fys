# 🥤 Copiloto de Vendas com IA para Atendimento ao Cliente - FYS

> Projeto desenvolvido como desafio do **Bootcamp Heineken - Inteligência Artificial Aplicada a Vendas**, promovido pela DIO.

---

# 📖 Sobre o Projeto

O **Copiloto de Vendas com IA** é um agente inteligente desenvolvido para apoiar vendedores, representantes comerciais e equipes de atendimento durante negociações envolvendo a marca **FYS**, pertencente ao **Grupo Heineken**.

A solução utiliza uma **Base de Conhecimento** construída a partir da documentação do desafio e da transcrição oficial da live da DIO, permitindo responder dúvidas, sugerir abordagens comerciais, tratar objeções e apoiar decisões durante o processo de vendas.

O objetivo não é substituir o vendedor, mas atuar como um **assistente inteligente**, fornecendo informações rápidas, organizadas e contextualizadas.

---

# 🎯 Objetivos

Este projeto foi desenvolvido para:

- Auxiliar vendedores durante negociações;
- Responder dúvidas sobre a marca FYS;
- Apresentar os diferenciais dos produtos;
- Tratar objeções comerciais;
- Sugerir estratégias de abordagem;
- Apoiar a priorização de clientes e oportunidades;
- Demonstrar a aplicação prática da IA Generativa em vendas.

---

# 🚀 Funcionalidades

O agente é capaz de:

- 🧠 Explicar informações sobre a marca FYS;
- 🥤 Apresentar o portfólio de produtos;
- ❓ Responder perguntas frequentes;
- 🛡️ Auxiliar no tratamento de objeções;
- 📈 Recomendar estratégias comerciais;
- 🤝 Apoiar vendedores durante visitas a clientes;
- 📚 Utilizar uma Base de Conhecimento organizada.

---

# 📂 Estrutura do Projeto

```text
copiloto-vendas-fys/
│
├── AGENTS.md
├── system-prompt.md
├── README.md
│
└── knowledge/
    ├── contexto-da-marca.md
    ├── produtos.md
    ├── perguntas-frequentes.md
    ├── objecoes.md
    ├── estrategia-comercial.md
    └── transcricao-live.md
```

---

# 🧠 Arquitetura do Projeto

O projeto foi organizado seguindo o conceito de **RAG (Retrieval-Augmented Generation)**, separando conhecimento, comportamento e regras do agente.

### Base de Conhecimento (`knowledge/`)

Contém todas as informações utilizadas pelo agente para responder às perguntas.

- Contexto da marca
- Produtos
- Perguntas frequentes
- Objeções comerciais
- Estratégias de vendas
- Transcrição da live

---

### AGENTS.md

Define:

- identidade do agente;
- objetivo;
- público-alvo;
- comportamento;
- estilo de comunicação;
- responsabilidades.

---

### system-prompt.md

Contém as instruções que orientam o funcionamento do agente, como:

- utilização da base de conhecimento;
- fluxo de raciocínio;
- regras de resposta;
- limitações;
- comportamento esperado.

---

# 💡 Como a IA é utilizada

O agente atua como um **Copiloto de Vendas**, oferecendo suporte durante o atendimento comercial.

Exemplos:

- sugerir argumentos de venda;
- responder dúvidas sobre produtos;
- apoiar vendedores durante negociações;
- tratar objeções;
- recomendar próximos passos.

---

# 💬 Exemplo de Utilização

### Pergunta

```text
Nunca ouvi falar da FYS.
```

### Resposta

```text
A FYS é a marca de refrigerantes do Grupo Heineken, criada para oferecer bebidas com menos açúcar, sabores diferenciados e uma comunicação moderna.

A marca busca atender consumidores que desejam novas opções de refrigerantes, mantendo qualidade e sabor.
```

---

### Pergunta

```text
Como convencer uma padaria a vender FYS?
```

### Resposta

```text
Uma boa estratégia é apresentar a marca como uma opção complementar ao portfólio do estabelecimento.

Destaque que a FYS pertence ao Grupo Heineken, possui produtos com menos açúcar e sabores diferenciados.

Sugira um pedido inicial reduzido para diminuir o risco percebido pelo comerciante.
```

---

# 📚 Base de Conhecimento

A solução foi construída utilizando informações provenientes de:

- Documentação oficial do desafio;
- Transcrição da live da DIO sobre a marca FYS;
- Contexto de negócio apresentado pela Heineken.

---

# 🛠️ Tecnologias Utilizadas

- Markdown
- Engenharia de Prompt
- IA Generativa
- Base de Conhecimento
- Git
- GitHub

---

# 🎓 Aprendizados

Durante o desenvolvimento deste projeto foram aplicados conceitos como:

- Engenharia de Prompt;
- Construção de agentes de IA;
- Organização de bases de conhecimento;
- Estruturação de documentação técnica;
- Aplicação de IA em vendas e atendimento ao cliente.

---

# 🔮 Melhorias Futuras

- Integração com APIs de modelos de IA.
- Interface web para interação com o agente.
- Integração com CRM.
- Sugestão automática de argumentos comerciais.
- Priorização inteligente de clientes.
- Geração de mensagens para WhatsApp.
- Dashboard de oportunidades comerciais.

---

# 👨‍💻 Autor

**Washington Alves da Silva**

- Técnico em Automação Industrial
- Estudante de Programação
- Participante do Bootcamp Heineken - IA Aplicada a Vendas

GitHub:

https://github.com/wscaxinha

---

# 📜 Licença

Este projeto foi desenvolvido exclusivamente para fins educacionais como parte do desafio da DIO em parceria com a Heineken.