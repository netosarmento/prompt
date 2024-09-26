# prompt
Engenharia de Prompt

# Algoritmos 

- Aprendizado Supervisionado 

Orientando ao modelo, fornecer base matemática, ou lógica de padrões.

- Aprendizado não Supervisionado 

Objetivo é agrupar dados, para chegar a um padrão com ajuda da IA.

- Aprendizado por Reforço

Agente que interage com o ambiente recebendo feedback's. Para maximizar respostas positivas.



# IA's

https://gamma.app/

Image generator : https://ideogram.ai/

Automações : https://manychat.com/pt

ChatGPT, Bing, Bard, LuzAI

Legendar - app blink

Leonardo Aí, MidJourny


you.com , ElevenLabs, D-ID, HeyGen

labs.heygen.com

tradução 

## Processamento de Linguagem Natural 

- Ensinar IA através de deep learning.
- Análise Semântica.
- Desambiguídade Semântica.

- Redes de Deep Learning : Fazer o base de dados, para interpretação de textos e palavras. Aspectos: Morfologia, Sintaxe, Semântica e Pragmatismo.

Pragmático: É o ramo da linguística que estuda linguagem no contexto de seu uso na comunicação.


Com análise detalhada da composição, derivação e flexão das palavras em suas utilizações.

- Algoritmo: NeedFoward ( NN Convolucional ) , LSTM ( já ensina sobre ambiguidade ), NTM ( Neutral Machining Translation )

- WordEmbendig : as palavras são transformadas em vetores, com sua derivações, para serem analisadas e criar um contexto.

 ## Prompts

 - Solução de Poucos Disparos : as soluções de poucos disparos, consiste em dar alguns modelos de entradas e saidas, para que assim se estabeleça um modelo.

 - Solução de Disparo Zero : Não é dada nenhuma entrada, ou modelo. Esse modelo consiste em que ele faça o modelo, baseando na descrição da tarefa.

 - Uso de Limitador e delimitador !
 - usar tag's <exemplo> </exemplo>
 - Refinar o prompt para obter respostas mais acertivas e consisas.
   Exemplos : Categorização, Pergunta e resposta sem contexto, Pergunta e resposta com contexto, lógico, matemático, Raciocinio em cadeia de pensamento.

A engenharia de prompts é a prática de projetar e otimizar instruções (prompts) para interagir eficazmente com modelos de linguagem de inteligência artificial. Essa técnica visa obter respostas mais precisas, relevantes e úteis desses sistemas.

Diretrizes para a Criação e Otimização de Prompts
A criação de prompts bem formulados e otimizados envolve:

Clareza e Precisão: Criar instruções específicas e bem estruturadas.

Contexto: Fornecer informações de fundo relevantes.

Exemplos: Incluir exemplos para orientar o modelo.

Restrições: Definir limites ou condições para as respostas.

Formato: Especificar o formato desejado para a saída.

Iteração: Refinar prompts com base nos resultados obtidos.

Entendendo os Parâmetros de Inferência
Os parâmetros de inferência são os ajustes e configurações que influenciam como o modelo de Inteligência Artificial gera previsões ou respostas quando está em uso. Eles são aplicados após o modelo ter sido treinado e ajudam a definir a forma como o modelo lida com novos dados.

Inferência é o processo de aplicar um modelo treinado a novos dados para gerar previsões, classificações ou respostas.

Dentre os principais parâmetros, temos:

| Parâmetro         | Descrição                                                                 | Tipo de Aplicação                                           |
|-------------------|---------------------------------------------------------------------------|-----------------------------------------------------------|
| System prompts     | Instruções iniciais que ajustam o comportamento e respostas do modelo.   | Sistemas que requerem personalização de comportamento.    |
| Temperature        | Controla a "aleatoriedade" e "criatividade" das respostas.               | Aplicações que exigem criatividade ou precisão.           |
| Top P              | Define a gama de opções para o próximo token.                            | Assistentes virtuais e chatbots.                          |
| Top K              | Limita a seleção de tokens aos K mais prováveis.                         | Geração criativa (ex: histórias, diálogos para jogos).    |
| Maximum Length     | Define o número máximo de tokens na resposta.                            | Respostas concisas.                                       |
| Stop Sequences     | Strings específicas que fazem o modelo parar de gerar mais texto.       | Controle de conteúdo em descrições e FAQs.               |


Entrada
A entrada consiste no recurso de texto do Claude 3 para o qual você deve retornar a descrição. Neste contexto, os seguintes recursos são considerados válidos para este desafio de código:

"Geração de conteúdo"
"Redação e revisão"
"Sumarização"
"Análise e interpretação de texto"
Saída
A saída esperada é a descrição associada ao recurso fornecido como entrada. Seguem as saídas possíveis, listadas aleatoriamente, para que você possa analisar e associar corretamente:

"Sintetizar artigos extensos ou documentos em resumos breves"
"Oferecer percepções e esclarecer conceitos complexos"
"Desenvolver conteúdo com base em instruções ou diretrizes"
"Auxiliar na criação de textos e revisão de materiais escritos"
