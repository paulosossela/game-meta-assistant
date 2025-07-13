# NLW Agents

Projeto desenvolvido durante o evento **NLW 20 - Next Level Week** da Rocketseat, focado em criar um assistente de meta para jogos utilizando inteligência artificial.

## 🎮 Sobre o Projeto

O NLW Agents é um assistente inteligente que fornece estratégias, builds e dicas para jogos populares como Valorant, League of Legends e CS:GO. O projeto utiliza a API do Google Gemini para gerar respostas contextualizadas e atualizadas sobre o meta atual dos jogos.

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura da aplicação
- **CSS3** - Estilização com animações e gradientes
- **JavaScript (Vanilla)** - Lógica da aplicação
- **Google Gemini API** - Inteligência artificial para respostas
- **Showdown.js** - Conversão de Markdown para HTML
- **Google Fonts** - Tipografia (Inter e Rajdhani)

## 📋 Pré-requisitos

- Navegador web moderno
- API Key do Google Gemini

## ⚙️ Configuração e Setup

1. **Clone o repositório:**

   ```bash
   git clone [url-do-repositorio]
   cd nlw-agents
   ```

2. **Obtenha uma API Key do Google Gemini:**

   - Acesse [Google AI Studio](https://makersuite.google.com/app/apikey)
   - Crie uma nova API Key
   - Guarde a chave para usar na aplicação

3. **Execute o projeto:**

   - Abra o arquivo `index.html` em seu navegador
   - Ou use um servidor local:

     ```bash
     # Com Python
     python -m http.server 8000

     # Com Node.js (npx)
     npx serve .
     ```

4. **Configure a aplicação:**
   - Insira sua API Key do Gemini no campo correspondente
   - Selecione o jogo desejado
   - Digite sua pergunta sobre estratégias, builds ou dicas

## 🎯 Funcionalidades

- **Seleção de Jogos:** Suporte para Valorant, League of Legends e CS:GO
- **Respostas Contextualizadas:** Baseadas no meta atual e patch mais recente
- **Interface Responsiva:** Design moderno com animações CSS
- **Conversão Markdown:** Respostas formatadas automaticamente

## 📁 Estrutura do Projeto

```
nlw-agents/
├── index.html          # Página principal
├── script.js           # Lógica JavaScript
├── style.css           # Estilos CSS
├── assets/             # Imagens e recursos
│   ├── bg.jpg         # Background
│   └── logo.png       # Logo do projeto
└── README.md          # Documentação
```

## 🔧 Padrões de Projeto

- **Separação de Responsabilidades:** HTML (estrutura), CSS (apresentação), JS (comportamento)
- **Modularização:** Funções específicas para cada funcionalidade
- **Tratamento de Erros:** Validação de formulários e tratamento de exceções
- **UX/UI:** Feedback visual durante carregamento e estados de erro

## 🚀 Como Usar

1. Acesse a aplicação no navegador
2. Insira sua API Key do Google Gemini
3. Selecione o jogo (Valorant, LoL ou CS:GO)
4. Digite sua pergunta sobre estratégias, builds ou dicas
5. Clique em "Perguntar" e aguarde a resposta da IA

## 📝 Licença

Este projeto foi desenvolvido durante o evento NLW 20 da Rocketseat para fins educacionais.

---

**Desenvolvido com 💜 durante o NLW 20 - Next Level Week da Rocketseat**
