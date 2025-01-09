# Banco de Dados para empresa Prime Park

Crição de Banco de dados para empresa Prime Park com base no seu modelo de negócio.

| :placard: Vitrine.Dev |     |
| -------------  | --- |
| :sparkles: Nome        | **Banco de Dados Prime Park**
| :label: Tecnologias | SQL, SQL Power Architect
| :rocket: URL         | https://url-deploy.com.br

<!-- Inserir imagem com a #vitrinedev ao final do link -->
![image](https://github.com/PedroMoeziaJr/Banco_de_Dados_Prime_Park/assets/112977342/037bf9f6-af3f-40df-9eb2-a4a09793c8ee#vitrinedev)

## Detalhes do projeto

A Prime Park é uma empresa especializada na administração de estacionamentos de diversos portes. Muitos dos estacionamentos gerenciados pela empresa contam com sistemas automatizados em suas operações.

Entretanto, no que diz respeito à gestão administrativa, ainda não há um sistema informatizado robusto que permita, no futuro, a criação de modelos de Business Intelligence (BI).

Diante desse cenário, o primeiro passo é desenvolver um banco de dados baseado no modelo de negócios da Prime Park.

Antes de iniciar o projeto, foi necessário elaborar um Glossário Comercial/Dicionário da empresa para padronizar os conceitos e garantir alinhamento entre todas as partes envolvidas.

Nota: Algumas informações foram adaptadas para que possam ser divulgadas publicamente.

# Fases do Projeto.

## 1 Fase - Criação do Dicionário.

Após uma reunião com os colaboradores da Prime Park, foi elaborado um dicionário comercial. Esse documento serviu como base para padronizar termos e conceitos, permitindo o avanço estruturado no desenvolvimento do banco de dados.

## 2 Fase - Regras do negócio.

Conforme discutido em reunião com os colaboradores da Prime Park, foram definidas algumas diretrizes essenciais para o funcionamento da empresa:

Embora a Prime Park administre estacionamentos de terceiros, sua principal fonte de receita provém dos clientes que estacionam seus veículos.
Cada estacionamento apresenta características únicas, como número de vagas, tabela de preços, tipo de cliente, quantidade de colaboradores, meio de cobrança e horário de funcionamento.
A Matriz da empresa é responsável por registrar todas as fontes de receita de cada estacionamento.
As fontes de receita de cada estacionamento são categorizadas em três grupos: Clientes Rotativos, Clientes Mensalistas e Convênios.
A Matriz também é encarregada do pagamento das despesas de todos os estacionamentos administrados, bem como da gestão da folha de pagamento dos colaboradores de cada estacionamento.
A Matriz tem a responsabilidade de registrar e conferir os pagamentos dos clientes mensalistas e conveniados.

## 3 Fase - Modelagem de Dados.

Com base nas informações fornecidas pelos colaboradores da Prime Park, desenvolvemos a seguinte modelagem dos dados:

![image](https://github.com/PedroMoeziaJr/Banco_de_Dados_Prime_Park/assets/112977342/625fe1ae-299e-4b25-a215-a58b8be958d5)

![image](https://github.com/user-attachments/assets/863e2676-a8c0-4bfb-bd54-2897ce4aa721)

## 4 Fase - Criação do Banco de Dados.

A partir dessa modelagem criamos o código em linguagem SQL em anexo.




