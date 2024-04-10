# mslearn-explore_speech-analyze-text

## Explicando o Projeto
 O projeto foi dividido em 2 etapas, estruturado conforme os arquivos de referência:
 - [Explore Speech Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/09-speech.html).
 - [Analyze text with Language Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html)

<strong> A IDEIA DO PROJETO ERA SALVAR APENAS O QUE É RESULTADO DO PROCESSO DE ANÁLISE DE SENTENÇAS. PARA FINS DE APRENDIZADO E DEMONSTRAÇÃO, RESOLVI EXPLORAR AS DEMAIS OPÇÕES E TECNOLOGIAS DO AZURE (como o SPEECH). O RESULTADO DO ANÁLISE DE SENTENÇAS SE ENCONTRA NA PARTE DE "Analyze text with Language Studio"</strong>

## Explore Speech Studio

### Passos
- Configuração de Workspace
- Uso do Serviço de Azure AI Speech conforme dados da referência da Azure
- Criação do Recurso Azure AI Speech
- Uso dos inputs disponibilizados na referência do projeto
- Conversão de fala em texto em tempo real
- Anexar arquivo WhatAICanDo.m4a, disponibilizado na pasta inputs/
- Resultado em texto aparecerá em output

#### Text Output:
```
AI enables us to build amazing software that can improve healthcare, enable people to overcome physical disadvantages. Empower smart infrastructure, create incredible entertainment experiences, and even save the planet. 
````
Também disponível em output/text_output.txt

O resultado JSON do Speech se encontra em output/json_text_output.txt

## Analyze text with Language Studio

### Passos
- Configuração de Workspace
- Uso do Azure AI Language conforme dados da referência da Azure
- O projeto explorará reviews de hotel
- Criação de um serviço de Linguagem
- Selecionar CLassify Text
- Selecionar Analyze sentiment and mine opinions

#### Adicionar o texto da review_1-sentence_1 abaixo:

```
 Tired hotel with poor service
 The Royal Hotel, London, United Kingdom
 5/6/2018
 This is an old hotel (has been around since 1950's) and the room furnishings are average - becoming a bit old now and require changing. The internet didn't work and had to come to one of their office rooms to check in for my flight home. The website says it's close to the British Museum, but it's too far to walk.
```

- Output dessa sentença se encontra em output/review_1-sentence_1.png

#### Adicionar o texto da review_2-sentence_1 abaixo:

```
 Good Hotel and staff
 The Royal Hotel, London, UK
 3/2/2018
 Clean rooms, good service, great location near Buckingham Palace and Westminster Abbey, and so on. We thoroughly enjoyed our stay. The courtyard is very peaceful and we went to a restaurant which is part of the same group and is Indian ( West coast so plenty of fish) with a Michelin Star. We had the taster menu which was fabulous. The rooms were very well appointed with a kitchen, lounge, bedroom and enormous bathroom. Thoroughly recommended.
```

- Output dessa sentença se encontra em output/review_2-sentence_1.png


#### Adicionar o texto da review_3-sentence_1 abaixo:

```
Very noisy and rooms are tiny The Lombard Hotel, San Francisco, USA 9/5/2018 Hotel is located on Lombard street which is a very busy SIX lane street directly off the Golden Gate Bridge. Traffic from early morning until late at night especially on weekends. Noise would not be so bad if rooms were better insulated but they are not. Had to put cotton balls in my ears to be able to sleep–was too tired to enjoy the city the next day. Rooms are TINY. I picked the room because it had two queen size beds–but the room barely had space to fit them. With family of four in the room it was tight. With all that said, rooms are clean and they’ve made an effort to update them. The hotel is in Marina district with lots of good places to eat, within walking distance to Presidio. May be good hotel for young stay-up-late adults on a budget
```

- Output dessa sentença se encontra em output/review_3-sentence_1.png


