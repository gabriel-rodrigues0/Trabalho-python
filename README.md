<div align="center">

# Jogo de Adivinhação

Jogo de terminal em Python para adivinhar o número sorteado, com níveis de dificuldade e pontuação.

<img src="https://img.shields.io/badge/Python-0D0D0D?style=for-the-badge&logo=python&logoColor=FF1A2B" alt="Python" />

</div>

## Sobre

Trabalho de programação do ensino médio técnico em Informática (2023). O programa sorteia um número e o jogador tenta acertá-lo pelo terminal, recebendo dicas a cada erro.

## Funcionalidades

- `tb.py`: menu com três níveis — Fácil (1 a 10, 4 tentativas), Médio (1 a 50, 6 tentativas) e Difícil (1 a 100, 7 tentativas) —, dicas de "maior" ou "menor" e pontuação por nível (10, 25 e 50 pontos)
- `import random.py`: versão inicial, em que o jogador define o intervalo do sorteio e tem tentativas ilimitadas

## Tecnologias

- Python 3 (módulo `random` da biblioteca padrão)

## Como executar

```
cd "TB programação"
python tb.py
```

## Estrutura

```
TB programação/
├── tb.py              # versão com níveis e pontuação
└── import random.py   # versão inicial com intervalo livre
```

---
<div align="center"><sub>Feito por <a href="https://github.com/gabriel-rodrigues0">Gabriel Rodrigues</a></sub></div>
