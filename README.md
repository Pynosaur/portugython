# Portugython
Essa é uma biblioteca Python que facilita a interação com a linguagem para não falantes de Inglês (com foco em Brazileiros)

O Brasil atulamente, 11/11/2022, é o país com o maior número de escolas de idiomas do mundo. \
Especialmente escolas do idioma Inglês. Contudo, um dos países que menos se fala outros idiomas \
comumente em sua sociedade. Pensando em uma forma de facilitar então a interatividade, o primeiro contato \
com um dos idiomas mais importantes da atualidade, Idioma Das Máquinas, a [Pynosaur](https://byteram.co/spin-offs/pynosaur/) decidiu criar uma biblioteca
que traduz as funções de Python. Criando então, uma nova camada de funções/classes/modulos/pacotes padrão traduzidas.


## Como contribuir

Para contribuir com código:

1. Crie um fork deste repositório
2. Crie uma `branch` nova a partir da branch `core`
  * Nomeie a sua `branch` no seguinte formato:
    - `feature/PLB-[número do PLB]-aaaa-mm-[nome do usuário]`, para features
    - `bugfix/PLB-[número do PLB]-aaaa-mm-[nome do usuário]`, para bugfix
3. Faça os `commits` comparando `across forks`
4. Siga o `playbook` para novas contribuições
5. Sempre atualize suas `branches` antes de começar a trabalhar em novas entregas
6. Formate seu código, [Black¹](https://pypi.org/project/black/) ou [Black²](https://gist.github.com/victorkolis/b1632e443e8f09e5d5addbc3619c0df6), antes de comitar novas alterações

## Objetivo
O objetivo dessa ferramenta é modificar as funções, e tudo aquilo que pertence a camada \
mais acessível do Python, sem modificar a gramática propriamente dita. Servindo como \
uma biblioteca que se comporta como tradução das funções/classes/modulos/pacotes padrão da linguagem.
Logo as palavras reservadas, também conhecidas como [`Keywords`](https://docs.python.org/pt-br/3/library/keyword.html) 
permanecem as mesmas.

## Install 
`pip install portugython`

## Code example

```python
from portugython import *

# Tradução de print
imprima('Olá, Portugython!')
```
