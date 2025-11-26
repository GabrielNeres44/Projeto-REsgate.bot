<img src="REsgate.bot.png" alt="Ícone do projeto">
REsgate.Bot — Chatbot Inteligente para Denúncias de Animais

O REsgate.Bot é um chatbot desenvolvido com n8n, Telegram, IA generativa e Google Cloud, criado para facilitar o reporte de animais perdidos, feridos ou em situação de risco.
Ele automatiza todo o processo de coleta, registro e encaminhamento das denúncias, garantindo agilidade, organização e acessibilidade.

🚀 Visão Geral

O projeto integra automação, inteligência artificial e comunicação via Telegram para permitir que qualquer pessoa denuncie rapidamente casos envolvendo animais.
Todas as informações coletadas são armazenadas automaticamente em uma planilha do Google Sheets e enviadas por email ao final da denúncia.

O propósito é oferecer uma solução simples e eficiente que apoia o resgate, o bem-estar animal e a gestão de ocorrências.

👥 Equipe

Gabriel Neres de Araújo

Cauê Fernando de Medeiros Reis

🧩 Tecnologias Utilizadas

n8n (automação e orquestração do fluxo)

Telegram Bot API

Groq (IA generativa)

Gemini AI Agent

Google Sheets

Gmail API

ngrok (exposição local para testes)

🐾 Público-Alvo

Pessoas que desejam reportar:

Animais abandonados

Animais feridos

Animais silvestres em situação de risco

Casos de perigo envolvendo fauna em áreas urbanas ou rurais

📌 Contexto

O abandono de animais representa um grave problema de:

Saúde pública (zoonoses)

Segurança (acidentes e ataques)

Sustentabilidade ambiental

O projeto busca reduzir esse impacto, criando um canal acessível de denúncias que facilita o encaminhamento dos casos para:

ONG’s especializadas

Órgãos de fiscalização

Entidades ambientais (como IBAMA)

🔄 Como Funciona o Fluxo do Chatbot
1️⃣ Início

O usuário envia /start no Telegram.
O bot pergunta se deseja iniciar uma denúncia.

2️⃣ Coleta de Informações

Caso o usuário responda "sim", o bot coleta:

Tipo de animal

Localização

Descrição da situação

Email do denunciante

A coleta é auxiliada por IA (Groq + Gemini AI Agent).

3️⃣ Menu Interativo

Após o email, o bot pergunta se o usuário deseja:

Adicionar mais informações

Encerrar a denúncia

4️⃣ Finalização

O bot:

Envia email ao usuário com o resumo da denúncia

Registra os dados no Google Sheets

Gera um ID único para cada ocorrência

Exibe mensagem de confirmação

🧠 Recursos Inteligentes

IA com memória contextual

Interpretação de texto usando modelos Groq e Gemini

Fluxos condicionais (if/switch)

Tratamento de erros (ex.: email inválido)

Interface simplificada via Telegram

✅ Requisitos do Projeto
Requisitos Técnicos

Chatbot implementado no n8n

Conexão com Telegram via BotFather

Integração com Google Sheets e Gmail

Uso de Agente de IA com memória

Fluxos condicionais e menus interativos

Registros automatizados dos dados da denúncia

Requisitos Funcionais

Iniciar conversa com /start

Perguntar ao usuário sobre iniciar denúncia

Coletar informações essenciais do caso

Validar email

Permitir adicionar mais dados

Finalizar denúncia com registro e email

Respostas automáticas em todas as etapas

Geração de ID único

Armazenamento seguro e organizado no Sheets

🐶 Objetivo Final

Criar uma ferramenta acessível, rápida e inteligente para promover o bem-estar animal, permitindo que denúncias sejam feitas e processadas com eficiência, conectando a sociedade a ONGs e órgãos responsáveis.