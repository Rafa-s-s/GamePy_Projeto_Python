# GamePy: Um Jogo Matemático Divertido

## Descrição
GamePy é um jogo simples e divertido de cálculos matemáticos. O objetivo é testar suas habilidades matemáticas enquanto você resolve operações de soma, subtração e multiplicação, geradas aleatoriamente, em diferentes níveis de dificuldade.

## Funcionalidades
- Escolha entre 4 níveis de dificuldade:
  - **Nível 1**: Operações com números entre 0 e 10.
  - **Nível 2**: Operações com números entre 0 e 100.
  - **Nível 3**: Operações com números entre 0 e 1000.
  - **Nível 4**: Operações com números entre 0 e 10.000.
- Resolução de operações matemáticas aleatórias (soma, subtração, multiplicação).
- Feedback imediato sobre respostas corretas ou erradas.
- Sistema de pontuação que contabiliza as respostas corretas.

## Estrutura do Projeto
```
GamePy/
│
├── .venv/               # Ambiente virtual (não incluso no repositório)
├── models/              # Módulos auxiliares do jogo
│   ├── __init__.py
│   ├── calcular.py      # Classe responsável por lógica matemática
│   └── teste.py         # Testes para a classe Calcular
├── game.py              # Arquivo principal do jogo
└── README.md            # Este arquivo
```

## Como Executar
### Pré-requisitos
Certifique-se de ter o Python 3.10 ou superior instalado no seu sistema.

### Passos
1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/GamePy.git
   ```
2. Navegue até a pasta do projeto:
   ```bash
   cd GamePy
   ```
3. Crie e ative um ambiente virtual:
   ```bash
   python -m venv .venv
   # Ative no Windows:
   .venv\Scripts\activate
   # Ative no Linux/Mac:
   source .venv/bin/activate
   ```
4. Instale as dependências (se houver):
   ```bash
   pip install -r requirements.txt
   ```
5. Execute o jogo:
   ```bash
   python game.py
   ```
## Explicação Interativa do Projeto
Para uma explicação detalhada e interativa do código, incluindo exemplos e a lógica por trás de cada parte, confira o seguinte arquivo:
- [GamePy: Explicação Interativa](https://github.com/Rafa-s-s/GamePy_Projeto_Python/blob/main/GamePy_Explica%C3%A7%C3%A3o.ipynb)

Você pode abrir o arquivo `.ipynb` diretamente no GitHub ou fazer o download para explorá-lo no Jupyter Notebook.


## Download do Projeto
Caso você prefira, pode baixar o projeto como um arquivo compactado diretamente:
- [Baixar GamePy.zip](https://github.com/Rafa-s-s/GamePy_Projeto_Python/releases/tag/1.0)

## Licença
Este projeto está licenciado sob a Licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

---

Divirta-se resolvendo cálculos e aprimorando suas habilidades matemáticas! 🚀
