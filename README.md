README.md
---

**Título do Projeto:** Chatbot de Suporte Técnico

**Descrição do Projeto:**

Este projeto implementa um chatbot de suporte técnico usando Python que:

- Carrega uma base de conhecimento de problemas e soluções.
- Utiliza o modelo de linguagem Gemini para gerar respostas a questões não encontradas na base de conhecimento.
- Gera números de chamado aleatórios.
- Mantém um histórico de atendimentos com notas de avaliação.
- Permite a visualização do histórico de atendimentos.

**Instalação:**

1. Instale o Python 3.9 ou superior.
2. Instale os seguintes módulos do Python:
    - numpy
    - json
    - datetime
    - random
    - google-generativeai
3. Crie uma conta de serviço e obtenha uma chave de API do Google para a API Generative AI.
4. Defina a variável de ambiente `GOOGLE_API_KEY` com a chave de API obtida.

**Uso:**

1. Execute o script `chatbot.py` para iniciar o chatbot.
2. Digite suas dúvidas ou problemas e siga as instruções.
3. Para visualizar o histórico de atendimentos, digite `historico` e pressione Enter.
4. Para sair do chatbot, digite `sair` e pressione Enter.

**Arquivos:**

* `chatbot.py`: Arquivo principal do chatbot.
* `base_conhecimento.json`: Arquivo JSON contendo problemas e soluções.
* `historico_atendimentos.json`: Arquivo JSON para armazenar o histórico de atendimentos.

**Créditos:**

* [Google Generative AI](https://cloud.google.com/language/ai/docs)

**Licença:**

Este projeto é licenciado sob a licença MIT.

----------------------------------------------------


README.md
---

**Description in ENGLISH
**Project Title:** Technical Support Chatbot

**Project Description:**

This project implements a technical support chatbot using Python that:

- Loads a knowledge base of problems and solutions.
- Utilizes the Gemini language model to generate answers to questions not found in the knowledge base.
- Generates random ticket numbers.
- Keeps a history of interactions with feedback ratings.
- Allows for viewing the history of interactions.

**Installation:**

1. Install Python 3.9 or above.
2. Install the following Python modules:
    - numpy
    - json
    - datetime
    - random
    - google-generativeai
3. Create a service account and obtain a Google API key for the Generative AI API.
4. Set the `GOOGLE_API_KEY` environment variable with the obtained API key.

**Usage:**

1. Run the `chatbot.py` script to start the chatbot.
2. Type in your questions or problems and follow the prompts.
3. To view the history of interactions, type `history` and press Enter.
4. To exit the chatbot, type `exit` and press Enter.

**Files:**

* `chatbot.py`: Main chatbot file.
* `knowledge_base.json`: JSON file containing problems and solutions.
* `interaction_history.json`: JSON file for storing the history of interactions.

**Credits:**

* [Google Generative AI](https://cloud.google.com/language/ai/docs)

**License:**

This project is licensed under the MIT License.
