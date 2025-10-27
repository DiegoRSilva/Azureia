# Desafio DIO: Explorando os Serviços de IA da Azure com Speech e Language Studio

Este repositório documenta a minha experiência prática com os serviços de IA da Azure, conforme proposto no desafio de laboratório da DIO.

## 🚀 Objetivo
O objetivo deste desafio foi explorar e documentar as funcionalidades do Azure Speech Studio (Serviços de Fala) e do Azure Language Studio (Serviços de Linguagem).

## 🛠️ Ferramentas Utilizadas
* Microsoft Azure Portal
* Azure Speech Studio
* Azure Language Studio
* GitHub (para documentação)

---

## 1. Azure Speech Studio (Serviços de Fala)
Nesta etapa, explorei as capacidades de conversão de texto em fala e de fala em texto.

### 1.1. Text-to-Speech (Texto para Fala)
* **Descrição:** Testei a funcionalidade de "Vozes Neurais" para gerar áudio a partir de um texto.
* **Configurações:** Utilizei ama voz em Português-Brasil e ajustei o tom para ser mais "animado".
* **Insights:** Fiquei impressionado com a naturalidade da voz gerada e a facilidade de ajuste fino dos parâmetros de fala.

### 1.2. Speech-to-Text (Fala para Texto)
* **Descrição:** Fiz o upload de um arquivo de áudio curto (uma gravação de voz minha) para testar a precisão da transcrição.
* **Resultados:** A transcrição identificou corretamente todo o vocabulário técnico"

---

## 2. Azure Language Studio (Serviços de Linguagem)
Aqui, foquei na capacidade da IA de entender e analisar linguagem natural.

### 2.1. Análise de Sentimento
* **Descrição:** Usei algumas avaliações de um restaurante para que a IA classificasse o sentimento.
* **Texto de Exemplo:** "A comida estava boa, mas o atendimento demorou muito."
* **Resultado da IA:** O serviço identificou um sentimento "Misto" (Mixed), com pontuações específicas para "comida" (Positivo) e "atendimento" (Negativo).

### 2.2. Extração de Frases-Chave
* **Descrição:** Forneci um parágrafo de uma notícia ou um bloco de texto técnico.
* **Resultados:** A IA extraiu com sucesso os tópicos principais.

### 2.3. Reconhecimento de Entidade Nomeada (NER)
* **Descrição:** Testei a capacidade do serviço de identificar e categorizar entidades em um texto (como nomes de pessoas, locais, organizações).
* **Texto de Exemplo:** "João Silva viajou para São Paulo para uma reunião na Microsoft."
* **Resultados:** O serviço identificou "João Silva" como [Pessoa], "São Paulo" como [Local] e "Microsoft" como [Organização].

## 💡 Conclusão
Este laboratório foi fundamental para entender o poder e a facilidade de uso dos serviços cognitivos da Azure. O Speech Studio é excelente para criar aplicações de voz acessíveis e com som natural, enquanto o Language Studio oferece insights profundos e rápidos sobre dados de texto não estruturados. Ambas as ferramentas são muito poderosas para o desenvolvimento de soluções de IA.
