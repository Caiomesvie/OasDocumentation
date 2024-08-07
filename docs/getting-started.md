# Getting Started

Este é um guia para ajudar você a começar a contribuir com o OAS. Aqui você encontrará informações sobre como configurar o ambiente de desenvolvimento, como compilar o projeto e entender a estrutura geral do simulador.

## Pré-requisitos

Instale as seguintes ferramentas antes de começar a contribuir com o OAS:

- [Visual Studio](https://visualstudio.microsoft.com/pt-br/)
- [Octave](https://www.gnu.org/software/octave/)


## Configurando o Ambiente de Desenvolvimento

O OAS é dividio em duas frentes principais de trabalho, as modificações na Unreal Engine e o próprio projeto do OAS. Portanto, é necessário configurar o ambiente de desenvolvimento para ambas as frentes.

### Unreal Engine 5.2

O OAS é baseado na Unreal Engine 5.2. Porém, foram feitas algumas modificações no código fonte da engine para alcançar os objetivos do projeto. Portanto, é necessário utilizar a versão modificada da Unreal Engine disponível no repositório do OAS.

Para configurar o ambiente de desenvolvimento, siga os passos abaixo:

1. Clone o repositório da Unreal Engine do OAS:

```bash
git clone 
```

2. Compile a Unreal Engine seguindo as instruções do repositório.

### OAS

Para configurar o ambiente de desenvolvimento do OAS é necessário apenas realizar o download do projeto e abrir o arquivo `OAS.uproject` na Unreal Engine modificada.
    