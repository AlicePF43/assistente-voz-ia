# assistente-voz-ia
# 🎧 Assistente de Voz com IA (Whisper + NLP + gTTS)

Este projeto implementa um assistente de voz simples, capaz de:

* 🎤 Captar áudio do usuário
* 📝 Transcrever fala em texto (Speech-to-Text)
* 🤖 Gerar respostas com Inteligência Artificial
* 🔊 Converter texto em áudio (Text-to-Speech)

---

## 🚀 Tecnologias Utilizadas

* **Python**
* **Whisper (OpenAI)** → Transcrição de áudio
* **Transformers (Hugging Face)** → Processamento de linguagem natural
* **gTTS (Google Text-to-Speech)** → Geração de áudio
* **Google Colab** → Execução do projeto

---

## ⚙️ Como Funciona

O sistema segue estas etapas:

1. 🎤 O usuário grava um áudio pelo navegador
2. 🧠 O Whisper converte o áudio em texto
3. 🤖 Um modelo de IA interpreta e gera uma resposta
4. 🔊 A resposta é convertida em áudio e reproduzida

---

## 🧠 Resumo do Projeto

O projeto consiste no desenvolvimento de um sistema de conversação por voz que integra tecnologias de Inteligência Artificial para permitir interação natural e multilíngue. A solução utiliza o modelo Whisper para converter a fala do usuário em texto (Speech-to-Text), modelos de processamento de linguagem natural da biblioteca Hugging Face para interpretar a entrada e gerar respostas, e o Google Text-to-Speech (gTTS) para transformar essas respostas em áudio (Text-to-Speech).

O funcionamento ocorre em quatro etapas principais: (1) captura do áudio do usuário via navegador com JavaScript e processamento em Python; (2) transcrição do áudio utilizando o Whisper; (3) processamento do texto e geração de resposta utilizando modelos de linguagem; e (4) conversão da resposta em voz por meio do gTTS, proporcionando uma experiência completa de interação por voz.

Como resultado, o sistema permite comunicação fluida entre usuário e máquina, com suporte a múltiplos idiomas, podendo ser aplicado em assistentes virtuais, automação, tradução em tempo real e soluções de acessibilidade.

---

## 🔄 Adaptação do Projeto

Inicialmente, o projeto previa o uso da API do ChatGPT para geração de respostas. No entanto, essa abordagem exige o uso de chave de API com billing ativo.

Para tornar o projeto acessível e totalmente funcional de forma gratuita, a etapa de geração de respostas foi adaptada para utilizar modelos da biblioteca **Hugging Face Transformers**.

Essa mudança permitiu:

* ✅ Eliminar a dependência de APIs pagas
* ✅ Executar o projeto integralmente no Google Colab
* ✅ Manter a funcionalidade de geração de linguagem natural

---

## 🧠 Exemplo de Uso

Você pode falar comandos como:

* "O que é inteligência artificial?"
* "Explique o que é a DIO"
* "Me dê um resumo disso"
* "Parar" → encerra o assistente

---

## 📂 Estrutura do Projeto

* `record()` → Captura áudio via navegador
* `Whisper` → Transcrição
* `Transformers` → Geração de resposta
* `gTTS` → Conversão para áudio

---

## ▶️ Como Executar

1. Abra o projeto no **Google Colab**
2. Instale as dependências:

```python
!pip install git+https://github.com/openai/whisper.git
!pip install transformers gTTS
```

3. Execute as células na ordem
4. Grave seu áudio quando solicitado

---

## ⚠️ Observações

* Não é necessário usar API paga
* O primeiro uso pode demorar (download dos modelos)
* Requer conexão com internet

---

## 💡 Possíveis Melhorias

* Interface com Streamlit
* Memória de conversa (chat contínuo)
* Personalização do assistente
* Integração com APIs externas

---

## 📌 Autor

Projeto desenvolvido para fins de estudo em Inteligência Artificial e Processamento de Linguagem Natural.

