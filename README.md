# Dashboard E-commerce #
Dashboard de um e-commerce com base nas orientações solicitadas pela empresa.


## Problema Proposto ##
Criar um painel gerencial para um e-commerce que almeja estudar suas vendas e assim, traçar a melhor estratégia para alavancar seus resultados.

Para criação do Dashboard foi fornecida duas bases de dados, uma com dados de vendas e outra com informações dos clientes.

Foi solicitado para criar duas páginas para que os analistas possam visualizar as métricas, e também que a abordagem fosse realizada seguindo um storytelling e com layout atrativo.

Os gráficos foram previamente solicitados pela gestão da área.


## Ferramentas utilizadas ##
Excel e Power BI


## Arquivo utilizado ##


## Instalando o Robot Framework e Bibliotecas Relacionadas ##
Você pode instalar o Robot Framework e as bibliotecas necessárias executando os seguintes comandos no terminal ou prompt de comando:
pip install --upgrade robotframework
pip install --upgrade robotframework-faker

## Estensões Vscode ##
Robot Framework Formatter 
Robot Framework Language Server
Robot Snippets
Vscode-icons

## Como executar ##
```bash
robot -d ./logs <nome_arquivo.robot>
```

Arquitetura

├── logs
    ├── .gitignore
│   ├── log.html
│   ├── output.xml
│   ├── report.html
│   
├── README.md
│   
├── resources
|   ├── keywords_gerar_massa.robot
    ├── keywords_post.robot
    ├── keywords_put.robot
    ├── login.robot
    ├── resource.robot
    ├── variables.robot
│   
├── tests
│   ├── company
        ├── postCompany.robot
        ├── putCompany.robot
│
├── users
│   ├── company
        ├── login_com_sucesso.robot
        ├── post.robot
