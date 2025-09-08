# 📘 Cálculo Numérico com Python

Este repositório contém notebooks Jupyter com implementações em **Python** de algoritmos e métodos clássicos de **Cálculo Numérico**, acompanhados de exemplos práticos e visualizações gráficas.

Os notebooks abrangem temas como:
- Métodos para cálculo de raízes de equações não lineares (Bisseção, Falsa Posição, Newton-Raphson, Secante)
- Solução de sistemas lineares (Eliminação de Gauss, Fatoração LU, Jacobi, Gauss-Seidel)
- Interpolação polinomial e ajuste de curvas (Lagrange, Newton, Splines)
- Integração numérica (Trapézio, Simpson, Quadraturas)
- Resolução numérica de equações diferenciais ordinárias (Euler, Runge-Kutta)

## Como executar

Você pode rodar os notebooks de duas formas:

### Localmente
Clone este repositório:
```bash
git clone https://github.com/seu-usuario/calculo-numerico.git
cd calculo-numerico
```

Crie um ambiente virtual (opcional, mas recomendado):
```bash
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows
```

Instale as dependências:
```bash
pip install -r requirements.txt
```

Inicie o Jupyter Notebook:
```bash
jupyter notebook
```

### Google Colab
Você também pode abrir os notebooks diretamente no **Google Colab**, sem instalar nada localmente. Basta clicar no link abaixo e substituir `seu-usuario` pelo nome correto do seu GitHub:

[![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/seu-usuario/calculo-numerico)

## Dependências
- Python 3.8+
- NumPy
- Matplotlib
- Jupyter

(Outras dependências podem ser adicionadas em `requirements.txt`.)

## Exemplos de equações utilizadas

### Método da Raiz Quadrada
$$
x_{n+1} = \frac{1}{2}\left(x_n + \frac{a}{x_n}\right)
$$

### Método da Raiz k-ésima (Newton-Raphson)
$$
x_{n+1} = \frac{(k-1)x_n + \tfrac{a}{x_n^{k-1}}}{k}
$$
