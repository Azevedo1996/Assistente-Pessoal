Assistente Pessoal com Python
Fala pessoal, essa é a Ana, uma assistente pessoal virtual que escuta os seus comandos de voz e executa-os!

Features:
⌚ Horário atual: "Que horas são?"
🔎 Pesquisa no Google: "Pesquisar objeto no Google"
🪙 Cotação de dólar, euro e bitcoin: "Qual a cotação do dólar no momento?"
📰 Últimas 5 notícias do momento: "Quais as últimas notícias?"
📽️ 5 filmes mais populares do momento: "Quais os filmes mais populares no momento?"
🎧 Abrir a melhor música, banda e álbum do mundo no Spotify: "Qual a melhor música do mundo?"
⛅ Clima/tempo: "Clima em São Paulo"
🔃 Tradutor para inglês e português: "Traduzir para o inglês"
📒 Criar e visualizar lembretes: "Criar novo lembrete" ou "Visualizar lembretes"
💻 Abrir programar na sua máquina: "Abrir Discord"
💤 Desligar computador em 1 hora ou meia hora: "Desligar computador em uma hora"
❌ Cancelar desligamento do computador: "Cancelar desligamento"
🙋🏽‍♀️ Fechar a assistente: "Fechar assistente"
Tecnologias utilizadas:
Python: linguagem de programação
Speech Recognition: reconhecimento de voz
gTTS: sintetização de voz
Playsound: executador de áudio
Beautiful Soup 4: para leitura de páginas elementos em páginas web
Translate
Outras: os, sys, webbrowser, urllib.request, json, datetime, requests
Como executar:
1. Instale Python na sua máquina, por meio deste link
2. Faça um clone desse repositório na sua máquina:
Crie uma pasta no seu computador para esse programa, recomendo colocar o nome Assistente Pessoal
Abra o git bash ou terminal dentro dessa pasta
Copie a URL do repositório
Digite git clone <URL copiada> e pressione enter
3. Instale as bibliotecas necessárias pelo terminal, dentro dessa pasta criada:
gTTS: pip install gTTS
playsound: pip install playsound
beautiful soup 4: pip install beautifulsoup4
speech recognition: pip install SpeechRecognition
translate: pip install translate caso apareça algum erro referente a alguma das bibliotecas importadas no programa, jogue o nome dela no Google e faça a instalação e passo a passo necessários
4. Baixe a ferramenta de lembretes:
Acesse o Notezilla e faça o download
Utilize o caminho C:\Program Files\Conceptworld\Notezilla para instalação
5. Crie sua chave para as APIs:
API de filmes:

Acesse o The Movie DataBase e faça seu cadastro
Em configurações, acesse API e crie uma nova chave
Copie a chave e cole no token da função filmes(), substituindo a frase <suachaveapi>
API de clima:

Acesse o Open Wheather Map e faça seu cadastro
Confirme o email recebido e em configurações, acesse suas API Keys
Copie a chave e cole no token da função clima(), substituindo a frase <suachaveapi>
6. Preencha os caminhos dos programas na sua máquina:
Pesquise os caminhos dos seguintes programas executáveis na sua máquina: Google Chrome, Visual Studio, Visual Studio Code, Discord e Notion
Abaixo do comentário abrir programas do computador, cole o respectivo caminho em cada chamada de função
Exemplo: os.startfile("C:\Program Files\Google\Chrome\Application\chrome.exe")
Caso queira adicionar ou deletar algum programa, faça isso utilizando o padrão do código
7. Execute o programa pelo terminal:
Digite python assistente.py
Estudos:
Na pasta estudos você escontra alguns códigos simples, que eu utilizei para aprender sobre as ferramentas, inclusive utilizando outras como espeak e pyttsx3
