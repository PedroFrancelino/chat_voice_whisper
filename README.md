
# Assistente de Voz com Whisper e ChatGPT 🎙️🤖

Este projeto implementa um assistente de voz completo utilizando Python e as APIs mais modernas de inteligência artificial.

## 🚀 Etapas do Projeto

### 1. Gravação de Áudio
Implementamos uma solução que captura o áudio diretamente no navegador via **Web API MediaDevices** (JavaScript) e o processa com Python no ambiente Colab.

### 2. Reconhecimento de Fala (Whisper)
Utilizamos o **OpenAI Whisper** para transcrever o áudio. O modelo se destaca pela precisão em diversos idiomas e nuances de fala.

### 3. Cérebro do Assistente (ChatGPT)
Integramos a API do **ChatGPT** para processar o texto transcrito e gerar respostas inteligentes e contextuais.

### 4. Síntese de Voz (gTTS)
Usamos a biblioteca **gTTS (Google Text-to-Speech)** para converter a resposta de texto em áudio, criando uma experiência de conversação fluida.

---
**Nota:** Para rodar este projeto, você precisará configurar sua `OPENAI_API_KEY` nos Secrets do Google Colab.
