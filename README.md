# Problema 3 - Sistemas Digitais
- A ideia do terceiro problema é a construção de oscilóscopio digital, com visualização de dados de um conversor ADC em tempo real. Por conta da situação de estamos enfrentando, os dados são adquiridos de um arquivo de texto, simulando valores que seriam lidos do conversor ADC.

## Objetivos
- Comunicação entre processos;
- Gráficos em tempo real.

## Desenvolvimento
- Foi desenvolvido um código na linguagem que C para geração de valores aleatórios e execução do GNUplot;
- Script para plotagem no GNUplot.

## Como executar
- Compilar e executar o arquivo pbl.c 
$ gcc pbl.c -o pbl -lm
$ ./pbl
