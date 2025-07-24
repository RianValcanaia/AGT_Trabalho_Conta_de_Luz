<div align="center" id="topo">

<img src="https://media.giphy.com/media/iIqmM5tTjmpOB9mpbn/giphy.gif" width="200px" alt="Gif animado"/>

# <code><strong> Calculadora de Fatura de Energia</strong></code>

<em>Trabalho da disciplina de Algoritmos </em>

<!-- adicionar aqui o uso das linguagens que eu passar-->
[![C Usage](https://img.shields.io/badge/C-100%25-blue?style=for-the-badge&logo=c)]()
[![Status](https://img.shields.io/badge/Status-Concluído-green?style=for-the-badge)]()
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Visite%20meu%20perfil-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/rian-carlos-valcanaia-b2b487168/)

</div>


## Índice

- [📌 Objetivos](#-objetivos)
- [📥 Entradas do sistema](#-entradas-do-sistema)
- [🛠️ Funcionalidades](#-funcionalidades)
- [📊 Exemplo de Execução](#-exemplo-de-execução)
- [📂 Como executar](#-como-executar)
- [👨‍🏫 Envolvidos](#-envolvidos)
- [📅 Curso](#-curso)
- [📄 Código-fonte](#-código-fonte)

## 📌 Objetivos
O objetivo principal deste trabalho é desenvolver um programa em C capaz de calcular o valor de uma fatura de energia elétrica com base em dados fornecidos pelo usuário.
* Coletar dados do cliente, como nome, UC, endereço e tipo de pessoa (física/jurídica).
* Registrar o consumo e, se aplicável, a geração própria de energia em kWh.
* Calcular o valor final da fatura considerando a bandeira tarifária (Verde, Amarela, Vermelha 1 e 2).
* Lidar com casos de geração de energia superior ao consumo.
* Calcular a data de vencimento da fatura.
* Permitir o cálculo de faturas para múltiplos clientes em uma única execução.
* Apresentar uma interface de texto limpa e organizada no terminal.

[⬆ Voltar ao topo](#topo)

## 📥 Entradas do sistema
O sistema solicita as seguintes informações ao usuário para gerar a fatura:
* Nome completo do cliente.
* Número da Unidade Consumidora (UC).
* Tipo de pessoa: `fisica` ou `juridica`.
* Se possui geração própria: `sim` ou `nao`.
* Endereço do cliente.
* Segundo endereço (apenas se for pessoa `fisica` com geração `sim`).
* Valor consumido em kWh.
* Valor gerado em kWh (apenas se tiver geração própria).
* Data da leitura no formato `dd/mm/aaaa`.
* Bandeira tarifária: `VERDE`, `AMARELA`, `VERMELHA 1` ou `VERMELHA 2`.

[⬆ Voltar ao topo](#topo)

## 🛠️ Funcionalidades

### 🔹 Funções Principais
* `main()` : Contém todo o fluxo principal do programa. É responsável por exibir a tela inicial, entrar em um loop para processar múltiplos clientes, coletar todas as entradas, realizar os cálculos da fatura e da data de vencimento, e exibir o resultado formatado na tela.


### 🔸 Funções Secundárias
* `limpaTela()`: Utiliza sequências de escape ANSI para limpar a tela do terminal, proporcionando uma experiência de usuário mais limpa e organizada entre as etapas.

[⬆ Voltar ao topo](#topo)

## 📊 Exemplo de Execução
1. O programa inicia com uma tela de boas-vindas artística e aguarda o usuário pressionar Enter.
2. O usuário insere os dados do cliente e do consumo, um por um, conforme solicitado pelo programa.
3. O sistema valida algumas entradas, como tipo de pessoa e bandeira, pedindo para tentar novamente em caso de valor inválido.
4. Após a inserção de todos os dados, a tela é limpa e a fatura final é exibida com todas as informações consolidadas: dados do cliente, valor a pagar, bandeira e data de vencimento.
5. O programa pergunta se o usuário deseja calcular a fatura para outro cliente, permitindo reiniciar o processo ou encerrar a execução.

[⬆ Voltar ao topo](#topo)

## 📂 Como executar
Para compilar e executar o programa, utilize o seguinte comando no seu terminal. A flag `-lm` é necessária para vincular a biblioteca matemática.
```bash
gcc trabalho.c -lm && ./a.out
```

[⬆ Voltar ao topo](#topo)

## 👨‍🏫 Envolvidos
* **Professor**: Everlin Fighera Costa Marques
* **Estudantes**:
  * [Rian Valcanaia](https://github.com/RianValcanaia)

[⬆ Voltar ao topo](#topo)

## 📅 Curso

* **Universidade**: Universidade do Estado de Santa Catarina (UDESC)
* **Disciplina**: Algoritmos
* **Semestre**: 1º

[⬆ Voltar ao topo](#topo)

## 📄 Código-fonte

🔗 [https://github.com/RianValcanaia/AGT_Trabalho_Conta_de_Luz](https://github.com/RianValcanaia/AGT_Trabalho_Conta_de_Luz)

[⬆ Voltar ao topo](#topo)
