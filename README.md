## Projeto Final da Imersão Dados 3 - Alura
![titulo](https://raw.githubusercontent.com/regiswcs/imersao-dados-desafio-final/main/img/imersao-dados.png)
<h5>Neste repositório você encontra o Projeto Final da Imersão Dados 3 da Alura.</h5>

O Evento Imersão Dados é um evento gratuito, focado em Ciência de Dados que está em sua terceira edição, realizado pela Alura, plataforma de cursos online voltados para Tecnologia. Esta edição foi realizada do dia 07/05/2021 ao 10/05/2021, com aulas diárias e desafios práticos com o intuito de demonstrar todas as etapas de um projeto real de Ciência de Dados, indo da coleta dos dados até a aplicação de um Modelo de Machine Learning, dando a base necessária para o participante concluir o Projeto final sobre o assunto proposto.

## Projeto: Aplicando Ciência de Dados em experimentos sobre novos medicamentos

![titulo](https://raw.githubusercontent.com/regiswcs/imersao-dados-desafio-final/main/img/experimentos-drogas.jpg)

#### Este projeto foi proposto baseado em uma competição organizada pelo [Kaggle](https://www.kaggle.com/c/lish-moa/overview/description), de um projeto do Broad Institute of MIT e Harvard, do Laboratory for Innovation Science em Harvard (LISH) e Biblioteca de Fundos Comuns do NIH de assinaturas celulares integradas em rede (LINCS), que tem o objetivo de avanço no desenvolvimento de medicamentos por meio de melhorias nos algoritmos de previsão do MoA ( Mecanismos de Ação ) que descrevem a atividade biológica de uma determinada molécula. 

### Um pouco sobre Drug Discovery ( Assunto Proposto )

**Como nasce um medicamento**

A criação de medicamentos tem uma série de etapas para garantir que eles sejam eficazes e seguros e envolve cientistas de várias áreas, como farmacêuticos, biólogos, químicos e médicos. Mas tudo isso só é possível depois que é identificado o mecanismo de funcionamento de uma doença e descoberta uma molécula capaz de influenciá-lo.

Fatores que podem dar início à criação de medicamentos: 
* Novas abordagens sobre o mecanismo de uma doença, o que permite projetar um medicamento que atue nele;
* **Testes que revelam efeitos de compostos moleculares que podem ser benéficos no tratamento de problemas de saúde;**:dart:
* Tratamentos já existentes que apresentam um efeito inesperado que pode ser útil para tratar alguma outra condição de saúde;
* Surgimento de novas tecnologias que permitem, por exemplo, levar uma substância até um local específico sem afetar o resto do organismo.

*Referência: [Roche](https://www.roche.com.br/pt/por-dentro-da-roche/como-nasce-um-medicamento.html)*

### Escopo do Projeto

Vamos buscar melhorar a previsão do MoA de um composto com base em sua assinatura celular, colaborando com o avanço na descorberta dos medicamentos.

Utilizaremos 2 Datasets fornecidos pela Alura, que estão na pasta chamada Dados. Um dataset contém informações sobre os experimentos e o outro com os resultados do MoA.

##### Datasets

 Dataset _**dados_experimentos.zip :**_


*   **id:**            Contém os ids de cada experimento.
*   **tratamento:**    Mostra se o exprimento teve adionada alguma droga ou não.
*   **tempo:**         Tempo do experimento: 24, 48 ou 72 horas.
*   **dose:**          Dosagem da droga neste experimento.
*   **[g-0...g-776]:** Colunas com todos genes analisados e seus respectivos valores de expressão: g-0 até g-775.
*   **[c-0...c-99]:**  Colunas com todas as células testadas e seus respectivos valores de viabilidade celular: c-0 até c-99.

Dataset _**dados_resultados.csv :**_


*  **id:** Contém os ids de cada experimento.

*  ***OBS:*** O restante das colunas são os Mecanismos de Ação(Moa) com a informação se foi ativo ou não para o experimento.


### Estrutura do projeto

É necessário que seu estudo seja bem organizado e estruturado, apresentando uma sequência lógica da análise. 

O projeto precisa expressar e justificar qual a linha de raciocínio foi criada e seguida durante o processo de elaboração. 


### Storytelling e conclusões

Parte da entrega de um estudo é mostrar para a comunidade qual o valor do seu projeto, dessa forma, contextualizar e aproximar o(a) interlocutor(a) é vital. 

É imprescindível que você pense que seu(sua) interlocutor(a), muitas vezes, não sabe do que o estudo trata e/ou não tem familiaridade com tecnologia e programação. Por isso, o notebook precisa ser explicativo de forma que a informação seja acessível para seu público alvo.

As conclusões parciais e a conclusão final são ótimos momentos para que a informação que você extraiu dos dados seja facilmente entregue ao(à) leitor(a). Ademais, você pode adicionar na conclusão as limitações do seu projeto, bem como as ideias para projetos futuros.   

### Pesquisas externas e cruzamento de dados

Do ponto de vista do estudo, é importante que outras fontes de informações sejam utilizadas para colaborar na construção da argumentação do projeto. E, do ponto de vista técnico, isso mostra adaptabilidade e antecipação, pois o cruzamento de informações é um passo muito fundamental no seu amadurecimento enquanto Data Scientist.

Porém, é preciso tomar bastante cuidado ao fazer essa junção: será avaliado o valor agregado à pesquisa, não somente as informações extras. 

Um exemplo: você pode pesquisar na literatura científica artigos que falam sobre drug discovery, com informações que você julgue relevantes, e utilizar esses dados e informações na sua argumentação e no desenvolvimento do seu storytelling.

* Finalmente teremos um novo README agora com as nossas alterações
![imagem indicando que nossas alterações foram salvas no README](https://user-images.githubusercontent.com/26041581/117192571-464d7080-adb8-11eb-9a70-2cef826ed24e.png)
Como escrever um bom README:

- Insira uma imagem;
- Coloque o nome do projeto;
- Descreva o projeto;
- Apresente o objetivo do projeto;
- Evidencie as particularidades do projeto;
- Explique sobre a estrutura dos dados;
- Exiba os links utilizados para a conclusão do projeto



