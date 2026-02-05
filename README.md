# Bot de Monitoramento de Preços (Amazon)

## Sobre o Projeto
Este é um projeto de **RPA (Robotic Process Automation)** desenvolvido para monitorar preços de produtos concorrentes em e-commerces.
O robô simula a navegação humana, coleta dados em tempo real e exporta para uma planilha Excel para análise gerencial.

## Tecnologias Utilizadas
* **Python 3.12**
* **Selenium WebDriver:** Para automação do navegador Edge.
* **Pandas:** Para estruturação e exportação de dados.
* **PyInstaller:** Para compilação do executável (.exe).

## Funcionalidades
- [x] Abertura automática do navegador (Edge).
- [x] Pesquisa inteligente de produtos.
- [x] Coleta de Título e Preço.
- [x] Tratamento de erros (caso o produto não tenha preço).
- [x] Geração automática de relatório em Excel (`.xlsx`).

## Como rodar este projeto
### Pré-requisitos
Você precisa ter o [Python](https://www.python.org/) instalado na sua máquina.

### Passo a passo
1. Clone o repositório:
   ```bash
   git clone [https://github.com/gabri3lvalim/bot-monitoramento-amazon.git](https://github.com/gabri3lvalim/bot-monitoramento-amazon.git)
