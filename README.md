# Análise de Sentimentos com IA

Este projeto demonstra como utilizei um serviço de IA para analisar o sentimento de algumas sentenças.

## Processo

1. Criei um repositório no GitHub chamado "analise-sentimentos-ia".
2. Adicionei um arquivo de texto com algumas sentenças na pasta "inputs".
3. Utilizei a API de Análise de Sentimentos da Azure para analisar as sentenças.
4. O resultado da análise foi salvo em um arquivo JSON.

## Insights

A análise da IA revelou que a maioria das frases analisadas expressam sentimentos positivos. Por exemplo, a frase "Eu adorei o novo filme! Foi muito divertido e emocionante." foi classificada como positiva, com 98% de confiança.

Por outro lado, frases com conteúdo negativo, como "O trânsito hoje estava horrível, cheguei atrasado no trabalho.", foram corretamente identificadas como negativas, com 97% de confiança.

Isso demonstra que a IA consegue identificar corretamente o tom emocional das frases, o que pode ser útil para diversas aplicações, como análise de opiniões de clientes ou monitoramento de redes sociais.

## Possibilidades

A análise de sentimentos pode ser utilizada em diversas aplicações, como:

* Análise de reviews de produtos
* Monitoramento de redes sociais
* Classificação de emails

## Código

```json
[
    {
        "sentence": "Eu adorei o novo filme! Foi muito divertido e emocionante.",
        "sentiment": "positive",
        "confidence": {
            "positive": 0.98,
            "neutral": 0.01,
            "negative": 0.01
        }
    },
    {
        "sentence": "O trânsito hoje estava horrível, cheguei atrasado no trabalho.",
        "sentiment": "negative",
        "confidence": {
            "positive": 0.01,
            "neutral": 0.02,
            "negative": 0.97
        }
    },
    {
        "sentence": "Estou ansioso para as férias, preciso relaxar um pouco.",
        "sentiment": "positive",
        "confidence": {
            "positive": 0.95,
            "neutral": 0.03,
            "negative": 0.02
        }
    },
    {
        "sentence": "Que dia lindo! O sol está brilhando e o céu está azul.",
        "sentiment": "positive",
        "confidence": {
            "positive": 0.99,
            "neutral": 0.01,
            "negative": 0.00
        }
    },
    {
        "sentence": "Não gostei da comida do restaurante, estava sem sabor.",
        "sentiment": "negative",
        "confidence": {
            "positive": 0.02,
            "neutral": 0.05,
            "negative": 0.93
        }
    },
    {
        "sentence": "A palestra foi muito interessante, aprendi muitas coisas novas.",
        "sentiment": "positive",
        "confidence": {
            "positive": 0.97,
            "neutral": 0.02,
            "negative": 0.01
        }
    }
]

