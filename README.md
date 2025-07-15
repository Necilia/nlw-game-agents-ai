# 🎮🤖 NLW Agents - Assistente de Meta com IA para Games

## ✨ Visão Geral do Projeto

Este projeto desenvolve um **assistente virtual interativo** projetado especificamente para gamers. Ele utiliza o poder da **Inteligência Artificial (IA) do Google Gemini** para fornecer dicas, estratégias e builds personalizadas para diversos jogos, tudo através de uma interface web intuitiva.

## 🚀 Funcionalidades

* **Formulário Interativo:** Permite ao usuário informar sua chave de API e fazer perguntas específicas sobre jogos e estratégias.
* **Integração com IA:** Conecta-se à Google Gemini API para processar as perguntas e gerar respostas inteligentes.
* **Conversão de Markdown:** As respostas da IA, que vêm em formato Markdown, são convertidas para HTML para uma visualização formatada e agradável (com negritos, listas, etc.).
* **Feedback Visual:** O botão de "Perguntar" oferece feedback visual (alterando texto e estado) durante o processamento da requisição.
* **Validação Básica:** Garante que os campos necessários sejam preenchidos antes de enviar a pergunta.

## 🛠️ Tecnologias Utilizadas

* **Front-end:**
    * `HTML5`: Estruturação da página e do formulário de interação.
    * `CSS3`: Estilização visual, incluindo responsividade e efeitos de interface.
    * `JavaScript`: Lógica principal da aplicação, manipulação do DOM e controle de eventos.
* **Integração com IA:**
    * `Google Gemini API (modelo Gemini 2.5 Flash)`: Para processamento de linguagem natural e geração das respostas da IA.
* **Bibliotecas Externas:**
    * `Showdown.js`: Biblioteca JavaScript para converter texto formatado em Markdown para HTML.

## ⚙️ Como Usar / Rodar Localmente

Siga estes passos para configurar e rodar o projeto em sua máquina local:

1.  **Clone o Repositório:**
    ```bash
    git clone [https://github.com/Necilia/nlw-game-agents-ai.git](https://github.com/Necilia/nlw-game-agents-ai.git)
    ```
    Navegue até a pasta do projeto:
    ```bash
    cd nlw-game-agents-ai # Ex: cd nlw-game-agents-ai
    ```

2.  **Obtenha sua Chave de API do Google Gemini:**
    * Acesse o [Google AI Studio](https://aistudio.google.com/app/apikey) e crie uma nova chave de API para o Gemini.

3.  **Insira a Chave de API na Aplicação:**
    * Abra o arquivo `index.html` ou simplesmente carregue o projeto no seu navegador (ex: usando a extensão Live Server do VS Code).
    * No campo "Informa a API Key do Gemini" na interface, **cole a sua chave de API**.

4.  **Faça Suas Perguntas:**
    * Selecione um jogo e digite sua pergunta sobre builds, estratégias ou dicas.
    * Clique em "PERGUNTAR" e aguarde a resposta da IA!

## 🧠 Aprendizados e Desafios

Neste projeto, tive a oportunidade de aprender e aplicar conceitos essenciais em:

* **Comunicação com IA:** Integrei a API do Google Gemini para o site "conversar" com a inteligência artificial e obter respostas dinâmicas.
* **Construção da Interface:** Desenvolvi a estrutura (HTML) e o visual (CSS) do site, garantindo uma experiência de usuário intuitiva.
* **Interatividade (JavaScript):** Tornei o site dinâmico, fazendo-o reagir às ações do usuário e exibir as informações da IA, superando desafios iniciais em lógica JavaScript.
* **Manejo de Dados e Erros:** Aprendi a lidar com os dados recebidos da IA e a gerenciar possíveis falhas na comunicação.
* **Uso de Ferramentas:** Explorei a utilização de bibliotecas externas para otimizar o desenvolvimento e a apresentação do conteúdo.

## 📄 Licença

Este projeto está licenciado sob a Licença MIT.