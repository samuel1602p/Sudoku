# 🧩 Sudoku Java Desktop

Um jogo de Sudoku clássico desenvolvido em **Java**, com foco em aplicar conceitos de Programação Orientada a Objetos (POO) e Arquitetura em Camadas. O projeto faz parte do meu portfólio de estudos em Análise e Desenvolvimento de Sistemas (ADS).

## 🚀 Funcionalidades

- **Geração de Tabuleiro:** O sistema inicia com um desafio pré-definido (números fixos).
- **Interface Intuitiva:** Desenvolvida com Java Swing, diferenciando visualmente os números fixos (pretos) dos inseridos pelo usuário (azuis).
- **Validação de Regras:** Sistema preparado para verificar as jogadas e garantir a integridade das regras do Sudoku.
- **Reinicialização Dinâmica:** Opção para limpar o tabuleiro e recomeçar o desafio atual.

## 🛠️ Tecnologias e Conceitos Utilizados

- **Linguagem:** Java 17+ (ou a versão que você estiver usando).
- **Interface Gráfica (GUI):** Java Swing & AWT.
- **Padrões de Projeto:**
  - **Observer/EventListener:** Utilizado para comunicação entre os componentes da interface e os serviços de lógica.
  - **Separação em Camadas:** Organização em pacotes (`model`, `service`, `ui`, `util`) para facilitar a manutenção e escalabilidade.
- **Componentização:** Criação de componentes customizados (ex: `NumberText`, `SudokuSector`) para uma interface mais limpa e reutilizável.

## 📁 Estrutura do Projeto

O projeto segue uma arquitetura modular:
- `model`: Representação dos dados (Espaços e Tabuleiro).
- `service`: Regras de negócio e lógica de eventos.
- `ui`: Toda a parte visual, dividida em telas, painéis e componentes customizados.
- `util`: Classes utilitárias e templates de tabuleiro.

## 🎮 Como Executar

1. Certifique-se de ter o **JDK** instalado em sua máquina.
2. Clone o repositório:
   ```bash
   git clone [https://github.com/samuel1602p/Sudoku.git](https://github.com/samuel1602p/Sudoku.git)
