# INTEGRA
INTEGRA é uma solução para integrar dados de fontes heterogêneas baseado em conceitos de interligação e correspondências de dados de diferentes níveis de representação.

# Descrição do Projeto

A abordagem de integração de dados INTEGRA oferce um conjunto de etapas e procedimentos para efetuar a integração de fontes de dados distintas.
Além de tratar os casos mais básicos de integração de dados, o INTEGRA é capaz de integrar fontes de dados heterogêneas quando a instância de uma das fontes age como descritor na outra fonte.

# Pré-requisito

Este projeto possui as seguintes dependências:

- [Java 8] (https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html) para rodar as bibliotecas e desenvolvimento, caso necessário.
- [Maven] (https://maven.apache.org/) para gestão de dependências, caso necessário.
- [Pentado PDI - Kettle 8.2] (https://sourceforge.net/projects/pentaho/) para rodar a solução INTEGRATeS (conjunto de arquivos .ktr)
- [ETL4LOD Plus] (https://github.com/johncurcio/ETL4LODPlus) para rodar e utilizar as bibliotecas de triplificação 
- [LIMES] (https://github.com/dice-group/LIMES) para rodar a solução de descoberta de ligações
- [Openlink Virtuoso] (https://virtuoso.openlinksw.com/) para armazenar os dados dos _datasets_ e os _matchers_

# Instalação

- [X] Instalar o JAVA 8 (JDK);
- [X] Instalar o Maven;
- [X] Instalar o Pentado PDI - Kettle;
- [X] Instalar os packages do ETL4LODPlus, conforme instruções do proprietário;
- [X] Instalar os packages do LIMES, conforme instruções do proprietário;

# Deploy
- Executar o comando: mvn clean install

# Publicação de Artigo Científico
- AVELINO, Jones de Oliveira; CORDEIRO, Kelli de Faria; CAVALCANTI, Maria Cláudia. An RDF based approach for integrating data at different levels of abstraction. In: SIMPÓSIO BRASILEIRO DE SISTEMAS MULTIMÍDIA E WEB (WEBMEDIA), 1. , 2020, Evento Online. Anais [...]. Porto Alegre: Sociedade Brasileira de Computação, 2020 . p. 59-66. Disponível em: https://sol.sbc.org.br/index.php/webmedia/article/view/13662



