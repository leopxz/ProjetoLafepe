# Projeto de Gerenciamento de dados em grandes volumes

## Contexto

Nesse projeto você vai encontrar um sistema de gerenciamento e automatização de processos e análise de dados. Este projeto é construído usando as bibliotecas Streamlit e Plotly em Python, com o objetivo de gerenciar e visualizar os dados em grande escala, onde você pode filtrar os dados cadastrados por mês, e também pode visualizar em formato de barras, pizza, histograma, linha, entre outros.

## Configuração

Para executar este projeto localmente, siga os passos abaixo para configurar o ambiente:

Clone o repositório:
```
git clone https://github.com/leopxz/ProjetoLafepe.git
```
Navegue até o diretório do projeto:
```
cd ProjetoLafepe
```
Instale as depêndencias necessárias:
```
pip install -r requirements.txt
```
```
pip install streamlit
```

## Execução

Para rodar o projeto, siga os seguintes passos:


Certifique-se de que as dependências foram instaladas.
Execute o script principal:
```
streamlit run main.py
```
O projeto estará disponível em localhost.

## Estrutura
A estrutura de pastas e arquivos do projeto segue o padrão abaixo:

ProjetoLafepe/
├── .vscode/            # Configurações do ambiente de desenvolvimento
├── Pages/Produtos/      # Páginas relacionadas aos produtos
├── controllers/         # Controladores para lógica de negócio e rotas
├── models/              # Modelos de dados e entidades
├── services/            # Serviços e lógica de aplicação
├── main.py              # Arquivo principal que inicia a aplicação
└── README.md            # Documentação do projeto




### Conjunto de Dados

Após abrir a aplicação e cadastrar um insumo, você pode experimentar importar uma base de dados no modelo CSV com **DADOS FICTÍCIOS** fornecido como base de dados, [Clicando AQUI](https://docs.google.com/spreadsheets/d/1bmImQvoLgk0EuptAjr5PAuKcvIfIV8ehGYtLTbzRBfI/edit?usp=sharing)

Para baixar o arquivo CSV e utilize-o na aplicação para visualizar os gráficos em grande escala:
Clique em: Arquivo > Fazer download > Microsoft Excel(.xlsx)

