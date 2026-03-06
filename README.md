
# Kenzo AI - Assistente Virtual Desktop

O Kenzo AI é um assistente virtual inteligente construído em Python, focado em produtividade e automação de tarefas no Windows. Com uma interface moderna e integração em nuvem, o Kenzo não apenas responde a comandos de voz, mas aprende continuamente com as preferências do usuário.

##  Principais Funcionalidades

- Controle por Voz & Respostas Naturais:** Utiliza reconhecimento de voz e síntese neural (Edge-TTS) para conversas fluidas em segundo plano.
-  Cérebro IA:** Integrado com a API do Google Gemini, capaz de manter contexto e responder a perguntas complexas.
-  Aprendizado Contínuo:** Sistema inteligente onde o assistente aprende novas regras ao ser corrigido pelo usuário, salvando o aprendizado no banco de dados.
-  Sincronização em Nuvem:** Sistema de Login via Firebase. As memórias e preferências do usuário são salvas na nuvem e sincronizadas em qualquer computador.
-  Automação de PC:
  - Controle de mídia (Spotify, YouTube Music, Volume, Pausar/Pular).
  - Abertura de aplicativos locais e sites.
  - Controle de janelas do Windows.
-  Gestão de Tempo:** Criação inteligente de eventos no Google Agenda e definição de alarmes/cronômetros rodando em Threads paralelas.
-  Execução em Segundo Plano:** Interface gráfica construída com `customtkinter`, minimizável para a bandeja do sistema (System Tray) para rodar silenciosamente.
- Método de criação de rotina (Curto):
Você: "Kenzo, criar rotina"
Kenzo: "Entendi. Qual deve ser a frase para ativar essa rotina?"
Você: "Modo Estudo"
Kenzo: "Certo. E quais ações eu devo fazer quando você disser Modo Estudo?"
Você: "Abra o bloco de notas e toque lofi no youtube"

##  Tecnologias Utilizadas

- **Linguagem:** Python
- **Interface:** CustomTkinter (GUI) e PyStray (System Tray)
- **Inteligência Artificial:** `google-genai` (Gemini 2.5 Flash)
- **Banco de Dados:** Firebase Realtime Database & Authentication (`pyrebase4`)
- **Voz e Áudio:** `speech_recognition`, `edge-tts`, `pyaudio`, `pygame`
- **Automação:** `pyautogui`, `pywhatkit`, `AppOpener`

##  Como executar localmente
- Baixe o .exe, execute e chame Kenzo para ele ativar, apartir dai faça seus pedidos.
- Utilize a conta:
  login*teste.kenzo.com*
  senha:*123456*
- Para feedbacks mande pelo email:kenaidesign22@gmail.com
