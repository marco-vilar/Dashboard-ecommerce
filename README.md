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
[Base de dados desafio.xlsx](https://github.com/user-attachments/files/18533541/Base.de.dados.desafio.xlsx)

## Formato Final ##
<img width="195" alt="Dashboard Página 1" src="https://github.com/user-attachments/assets/47947369-f3da-4e7f-8926-9e512da9674c" />

<img width="194" alt="Dashboard Pagina 2" src="https://github.com/user-attachments/assets/86085a05-98bb-4c96-b7f9-d126b844153e" />




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
