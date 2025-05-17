# SINALIA
🚀 Projeto Gemini AI: Desvendando a Linguagem e a Inclusão! 🚀
Bem-vindo ao repositório do meu projeto inovador desenvolvido com a inteligência artificial Gemini! Aqui você encontrará duas ferramentas poderosas e didáticas, focadas em democratizar o conhecimento e promover a inclusão linguística.

🤟 Guia de Libras AI
Seu parceiro digital para aprender Libras (Língua Brasileira de Sinais) de um jeito prático e visual!

O Que É?
O Guia de Libras AI é uma ferramenta essencial para quem quer aprender a se comunicar em Libras. Ele traduz frases, descreve os gestos para você e, o melhor de tudo, te dá links diretos para vídeos e imagens que mostram como fazer os sinais na prática!

✨ Principais Recursos
Tradução de Frases: Converte frases do português para o contexto dos sinais em Libras.
Explicação Detalhada dos Gestos: Receba descrições claras de como posicionar as mãos, fazer os movimentos e até a expressão facial para cada sinal.
Links Visuais Diretos: Acesse links para vídeos ou imagens que demonstram o sinal, facilitando o aprendizado visual.
Busca Inteligente: Se a frase completa não for encontrada, o AI é esperto o suficiente para quebrar a frase em palavras-chave e buscar os sinais individualmente.

🧠 Como Funciona?
Desenvolvido com o Google Gemini e o framework Google ADK, o Guia de Libras AI utiliza a ferramenta Google Search para vasculhar a web em busca dos sinais e recursos visuais mais adequados, garantindo que você tenha acesso rápido ao que precisa para aprender.

🛠️ Como Começar (Setup)
Para rodar esses projetos na sua máquina ou no Google Colab, siga os passos abaixo:

Pré-requisitos
Python 3.8+
Uma conta no Google Cloud e acesso à API do Google Gemini.
🔑 Configuração das Chaves de API
Ambos os projetos requerem uma chave da API do Google Gemini.

Obtenha sua chave da API do Google Gemini através do Google AI Studio.
No seu ambiente (seja no terminal ou no Google Colab):
- No Google Colab: Use a funcionalidade userdata.get() para armazenar sua chave com segurança. Crie um "Secret" chamado GOOGLE_API_KEY e cole sua chave lá.
- Localmente: Defina a chave como uma variável de ambiente (export GOOGLE_API_KEY="SUA_CHAVE_AQUI")

📦 Instalação das Dependências
Clone este repositório para o seu ambiente local:
terminal:
- git clone <URL_DO_SEU_REPOSITORIO>
- cd <NOME_DO_SEU_REPOSITORIO>

Instale as bibliotecas necessárias:
termianl:
- pip install google-genai google-adk requests

▶️ Como Rodar o Projeto
terminal:
python professor_portugues.py
