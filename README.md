# 🤖 SecretariaIA – ChatGPT com API Oficial OpenAI

Tutorial completo e direto ao ponto de como integrar o ChatGPT (GPT-3.5 / GPT-4) usando a **API oficial da OpenAI**, criando uma assistente virtual estilo **secretária inteligente** com Node.js e Express. A partir desse tutorial você poderá criar suas próprias automações e integrar nas suas aplicações, além de poder monetizar criando SaaS, Serviços On-line, Automações e Chatbots.

---

## 🚀 O Projeto

Crie um endpoint inteligente que responde automaticamente às perguntas de clientes com base nos dados da sua empresa. Ideal para **automação de atendimento**, **chatbots personalizados**, **assistentes de vendas** e muito mais.

---

## 🛠️ Tecnologias Utilizadas

- [x] JavaScript
- [x] Node.js 10+
- [x] Express.js
- [x] OpenAI API (GPT-3.5 ou GPT-4)
- [x] dotenv para segurança da API Key

---

## 📦 Instalação

```bash
git clone https://github.com/GuitasGarage/OpenAI-Tutorial-2025.git
cd OpenAI-Tutorial-2025
npm install

- OpenAI API Key
- Node 10+

## ⚓ Links de Referência
- OpenAI - API KEY: https://platform.openai.com/settings/organization/api-keys
- Assistir Videoaula: https://youtube.com
- Repositório no GitHub: https://github.com/GuitasGarage/OpenAI-Tutorial-2025
```

# ❔Como Usar

- Crie um arquivo .env com sua API KEY da OpenAI:
> OPENAI_API_KEY=sua-chave-aqui
- No arquivo server.js a porta está na 3000, por padrão, podendo ser alterada.
> Exemplo de url completa: http://localhost:3000/secretariaIA
- Dentro do diretório OpenAI-Tutorial, execute npm run dev (para modo desenvolvedor com hotreload) ou npm start. Lembre-se de ter instalado as dependências (npm i).
>  Exemplo: C:\Users\Fulano\OpenAI-Tutorial>npm run dev

- Faça uma requisição POST no endpoint:

> POST <strong>/secretariaIA</strong>

```bash
{
  "mensagemCliente": "Qual o horário de funcionamento ?",
}
```
> A IA sempre responde com um objeto JSON válido no formato:
```bash
{
  "openaiResponse": {
    "secretariaIA": "O horário de funcionamento da Pizzaria Bella Massa é todos os dias das 18h às 23h."
  }
}
