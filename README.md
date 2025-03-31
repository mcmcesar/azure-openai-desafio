# Simulação do Azure OpenAI Playground

Este repositório documenta minha exploração dos modelos de IA, simulando o funcionamento do Azure OpenAI Playground.

## Objetivo
Explorar como os modelos de IA geram texto e compreender os diferentes parâmetros que controlam o comportamento do modelo.

## O que Aprendi
- **Temperature**: Controla a criatividade. Valores baixos (0.2) geram respostas mais determinísticas, enquanto valores altos (0.8) incentivam criatividade.
- **Max Tokens**: Define o comprimento máximo da resposta. Exemplo: 50 tokens para frases curtas, 200 tokens para textos longos.
- **Top P**: Controla a diversidade das palavras escolhidas. Valores baixos (0.1) reduzem as variações, enquanto valores altos (0.9) aumentam a diversidade.
## Exemplos de Interações

Para ilustrar como os modelos de IA funcionam, criei vários exemplos práticos. Eles estão disponíveis na pasta [exemplos](exemplos/):

- [Exemplo 1: Geração de Texto Criativo](exemplos/exemplo1.txt)
- [Exemplo 2: Tradução](exemplos/exemplo2.txt)
- [Exemplo 3: Resumo de Texto](exemplos/exemplo3.txt)
- [Exemplo 4: Geração de Ideias Criativas](exemplos/exemplo4.txt)
- [Exemplo 5: Explicação Técnica](exemplos/exemplo5.txt)

## Exemplos de Interações
### Exemplo 1: Geração de Texto Criativo
**Prompt**: "Explique o que é fotossíntese."  
**Resposta**: A fotossíntese é o processo pelo qual as plantas convertem luz solar em energia química, usando água e dióxido de carbono para produzir glicose e oxigênio. Isso ocorre nas cloroplastos, onde a luz é captada e transformada em energia para alimentar a planta e liberar oxigênio. 
**Parâmetros**: Temperature = 0.7, Max Tokens = 50.

### Exemplo 2: Tradução
**Prompt**: "Traduza 'Olá, mundo!' para francês."  
**Resposta**: Bonjour, le monde!  
**Parâmetros**: Temperature = 0.2, Max Tokens = 10.

## Referências
- [Azure OpenAI Documentation](https://learn.microsoft.com/azure/cognitive-services/openai/)
