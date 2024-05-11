# imersao-ia-alura-google
Scriptizinho python de última hora no Google Colab para a imersão IA da Alura com o Google

### Script para ajudar uma escola de alunos de 6 a 10 anos.

## Situação Problema:

Uma informação importante para a escola são os totais de alunos. São até fixados em quadros pela escola para rápida visualização, como pode ser visto na imagem a seguir:

![](https://github.com/MIchaelDFernandes/imersao-ia-alura-google/blob/main/IMG_20240510_080321670.jpg?raw=true)

Tudo legal, até alguém perguntar: Quantos são meninas? E quantos são meninos?
Isso é uma informação importante, pode ser utilizada na compra de lembrançinhas para os alunos no dia das crianças por exemplo.
Então porque a quantidade de meninas e meninos não aparece na imagem? A resposta é simples: O sistema não exporta o gênero dos alunos. É um passando para o outro essa tarefa de olhar nome por nome, e não é só isso, mesmo a pessoa mais disposta pode contar errado em algum ponto, afinal é um humano.
Vamos dar uma chance ao Gemini 😁.

## Solução:
Um script python em formato de notebook no Colab que coleta os nomes dos alunos de vários arquivos .csv e pergunta para o Gemini se é um nome masculino ou feminino.
Depois pega os resultados e guarda em uma nova coluna chamada "gênero" e salva no formato Excel para todos utilizarem🤩.
O código será ajustado para a entrega final (afinal, ninguém vai querer abrir o Colab, eu mesmo nem sabia da sua existência😅), mas essa é a ideia.
