# Sistema de Monitoramento de Níveis de Água

Este projeto é uma simulação de um sistema de controle de níveis para um reservatório de água, desenvolvido em Python. O programa é executado via terminal e utiliza cores para indicar diferentes níveis de alerta, facilitando o monitoramento visual.

## 🚀 Funcionalidades

O sistema monitora 5 níveis de criticidade, cada um associado a uma cor específica utilizando a biblioteca `colorama`:

| Nível | Situação | Cor |
| :--- | :--- | :--- |
| Nível 1 | Muito baixo (crítico) | Vermelho |
| Nível 2 | Baixo | Amarelo |
| Nível 3 | Médio | Verde |
| Nível 4 | Alto | Ciano |
| Nível 5 | Muito alto (alerta) | Azul |

## 🛠️ Tecnologias Utilizadas

* **Python 3**: Linguagem de programação.
* **Colorama**: Biblioteca para estilização de cores no terminal.

## 📦 Pré-requisitos

Antes de executar o projeto, você precisa instalar a biblioteca `colorama`. Abra o seu terminal e digite:

```bash
pip install colorama
