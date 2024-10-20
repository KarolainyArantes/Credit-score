# **CRISP-DM na Prática** 


<img src="https://github.com/user-attachments/assets/e2849fa0-006c-458c-a7e1-4736c7009128" alt="Descrição do GIF" width="600" /> 


# **Análise de Dados: Utilizando CRISP-DM**


**Cross Industry Standard Process for Data Mining**: É uma metodologia usada por Cientistas de dados com objetivo de prever futuras falhas e soluções.

## **Descrição das Etapas CRISP-DM**  <img src="https://github.com/user-attachments/assets/592d2cd5-14d5-407b-ba40-8bdcee3cbcd1" alt="Descrição do GIF" width="30" /> 


### 1. **Dados**

 As três primeiras etapas da metodologia CRISP-DM mantém o foco em:
* Entedimento do negócio
* Entedimento dos dados 
* Preparação dos dados

|Entedimento do Negócio| Entedimento dos Dados| Preparação dos Dados|
|----------------------|----------------------|---------------------|
|Nesta etapa é definido o objetivo do projeto e as necessidades da empresa ou projeto em análise. Por isso é necessário que todos estejam bem informados e completamente alinhados.| Aqui será realizada perguntas como: "A empresa tem banco de dados? Os dados serão acessados de que forma? Quantas fontes de dados serão utilizadas? Quais serão os formatos dos dados? Os dados estão estruturados?" A partir delas é feita a coleta dos dados, tomando cuidado para que nenhuma informação importante fique de fora.| É preciso organizar os dados para conseguir enxergar o que eles contam. Deve se guiar por perguntas do tipo: " Como os valores nulos devem ser tratados? Os atributos estão nos formatos corretos? Será necessário fazer a fusão com outros dados? Quais variáveis serão utilizadas na modelagem?". Esta costuma ser a parte mais demorada e trabalhosa de todas, porém um bom trabalho aqui significa menos trabalho futuro.|

### 2. **Criação do Modelo**

As últimas três etapas tem como objetivo a criação do modelo, baseada nas etapas anteriores. É aqui que todo o trabalho anterior é testado e, caso necessário, refeito. São elas: 

* Modelagem 
* Avaliação
* Implementação

|Modelagem| Avaliação| Implementação|
|---------|----------|--------------|
|O tipo de modelagem a ser utilizada normalmente é definida de acordo com a necessidade do negócio e com o tipo de  variável a ser analisada, devem ser definidos quais atributos serão variáveis na construção deste modelo.| Avalia se o resultado corresponde à expectativa do projeto. Caso a resposta seja negativa ou a equipe considere espaço para melhorias, todas as forças devem ser direcionadas para fazer as mudanças necessárias.| Aqui o modelo deve ser colocado em produção, de modo a agregar valor para o negócio. Esse modelo deve ficar exposto para acesso, normalmente armazenado em nuvem ou em servidores locais da própria empresa.|



# Explicação da Análise <img src="https://github.com/user-attachments/assets/cc316519-b878-4211-8562-9123c44f33b7" alt="Descrição do GIF" width="50" /> 


**Análise realizada como desafio de formação em Data Science:** Com foco em aplicar a metodologia CRISP-DM de forma correta e coerente, respeitando todas as etapas. O projeto pode ser entendido por  qualquer pessoa que não seja da área de TI já que é apresentado com visuais e descrições em cada processo do começo ao fim.

## **Descrição da Análise** <img src="https://github.com/user-attachments/assets/592d2cd5-14d5-407b-ba40-8bdcee3cbcd1" alt="Descrição do GIF" width="30" /> 


O objetivo da análise é avaliar o **Credit Score** dos clientes. Entenda melhor o trabalho com os dados:

1. **Preparação dos dados**: 
Os dados desse projeto já havia passado pelo processo ETL, portando só foi realizada a remoção de alguns valores `null` para manter a coerência durante a modelagem.

2.  **Estudo de variáveis explicativas**:
 Realização de   cálculos, relaciomento entre  variáveis explicativas  e  variável resposta  e construção de visuais para uma melhor interpretação desses dados.

3. **Modelagem**: O modelo foi construído utilizando a técnica de modelagem **Random Forest**, ela foi escolhida por sua robusta capacidade em capturar padrões nos dados.

4. **Avaliação**: Os cálculos de acurácia do modelo foram realizados para atender as expectativas do projeto.

Esse foi os principais trabalhos realizados nos dados, para atender as necessidades do negócio e implementar o modelo para automatizar a aprovação de bons clientes ou negando clientes muito ruins, enviando os intermediários para uma análise manual.


