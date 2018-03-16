---
layout: default
---

# Introdução aos Sistemas Computacionais

## Índice

- [Introdução](#introdução)
- [Conteúdos](#conteúdos)
- [Provas](#provas)
- [Projeto Final](#projeto-final)
- [Recursos](#recursos)
- [Cheat Sheet](#cheat-sheet)

## [](#introdução)Introdução

É uma disciplina com um foco maior em _hardware_, considerada por alguns como uma das mais trabalhosas do primeiro semestre.

Para os calouros ela é ministrada pelo Professor Lamar, cuja reputação inclui provas difíceis e projetos finais trabalhosos, portanto é importante não ficar para trás na matéria.

Suas aulas são muito bem explicadas e organizadas, não hesite em tirar dúvidas caso não tenha entendido algo.

## [](#conteúdos)Conteúdos

Todas as aulas e conteúdos são previstos detalhadamente na ementa da disciplina.

Inicialmente é dado um breve resumo da história da computação, então ensinando-se sobre os componentes básicos de um computador com alguns detalhes a mais.

Após esse começo, o professor revisa a matéria de eletrodinâmica (nada além do que foi ensinado no Ensino Médio), e então o professor ensina sobre os processadores MIPS e seu conjunto de instruções (linguagem) chamado Assembly MIPS.

Como vocês vão ver, Assembly MIPS é uma linguagem de programação de baixíssimo-nível, e nela vocês terão que resolver alguns exercícios e programar um jogo usando um simulador chamado MARS para o [projeto final](#projeto-final) (todos estes termos ficarão mais claros conforme a matéria avança).

## [](#provas)Provas

A disciplina tem 3 provas.

A preencher (falar sobre cada prova e dicas)

## [](#projeto-final)Projeto Final

O projeto final dessa disciplina, como dito em [Conteúdos](#conteúdos), consiste em programar um jogo usando a linguagem Assembly MIPS que será ensinada antes.

Para não ficar estagnado na hora de programar o jogo ou cometer muitos erros difíceis de resolver, é recomendado que você programe alguns programas simples antes, como alguns exercícios fáceis das aulas práticas de APC, assim você irá se acostumar com a linguagem e irá perder menos tempo na hora de fazer o jogo.

O jogo será programado no simulador MARS, que contém simuladores de entrada e saída para teclado (Keyboard MMIO Simulator) e um "monitor" chamado Bitmap Display, detalhes de como usar serão ensinados pelo professor, mas se tiver dúvidas não hesite em perguntá-las para o professor, monitores ou veteranos.

Assim como em APC, o melhor jeito de entender como começar ou como estruturar seu jogo e seu código se trata de ler outros projetos já feitos, seguem alguns recomendados:
 * [2016/1 - Snake (Mikael Mello)](https://github.com/MikaelMello/snake-assembly-mips)
 * [2016/2 - Space Invaders (Giovanni Guidini)](https://github.com/Gguidini/SpaceInvaders)
 * [2017/1 - Pong Multiplayer (Vinicius)](http://www.mediafire.com/file/dg1835n6sl7kc5r/trabalho-isc-vinicius.zip)

Note que para usar imagens no simulador, elas precisam estar no formato binário (isso será explicado pelo professor), então para adicionar facilmente imagens ao seu jogo, crie ou procure as imagens que quiser e salve-as no formato Bitmap, então use uma ferramenta chamada [bmp2bin](https://github.com/MikaelMello/bmp2bin) para convertê-las para o formato binário e usá-las no projeto.

## [](#recursos)Recursos

A princípio, todos os recursos recomendados podem ser encontrados no moodle da disciplina.

## [](#cheat-sheet)Cheat Sheet

 * Mesmo que você não queira fazer o projeto por já estar passado ou ele não poder te ajudar a subir de menção, é recomendado que faça do mesmo jeito pois o que você aprender programando em Assembly MIPS será **extremamente** necessário na disciplina de OAC no terceiro semestre.
 * Se estiver tendo dificuldades para aprender como converter números de ponto flutuante (IEEE 754), siga [este método](#) (a implementar).
