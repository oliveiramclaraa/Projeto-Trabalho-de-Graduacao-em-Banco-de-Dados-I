# Projeto-Trabalho-de-Graduacao-em-Banco-de-Dados-I - 5º BD

Professor da Disciplina: Giuliano Bertoti

Aluna: Maria Clara Azevedo de Oliveira

RA: 1460281823033

## RESUMO

É certo que inserção no mercado de trabalho, bem como a mentoria de uma pessoa capacitada para dar a correta orientação, são essenciais para a reabilitação de jovens infratoras obrigadas ao cumprimento de medidas socioeducativas ("jovens"). O objetivo deste projeto é construção de uma plataforma digital funcional, nos moldes de uma rede social voltada para conexões profissionais, onde pessoas (físicas e jurídicas) engajadas com a causa da inclusão social ("voluntáries") possam oferecer vagas de trabalho e mentoria às jovens. A ferramenta também conta com uma parte voltada à orientação vocacional, com instruções para a elaboração de um currículum vitae virtual, e que associe etiquetas ("tags") ao perfil das jovens, correspondentes aos interesses e habilidades, conforme dados extraídos da construção do perfil. Com base nas características de voluntáries e jovens, bem como nas tags associadas a seus perfis, a plataforma buscará realizar recomendação de conexões, vagas e mentorias, utilizando inteligência artificial. A plataforma deverá contar com uma diagramação que priorize a usabilidade, visto que o público principal será a jovens, cuja maioria dispõe de pouco conhecimento técnico. 

Palavras-Chave: Inclusão; Jovens; Medidas Socioeducativas; Emprego; Reabilitação. 

## ABSTRACT

It is certain that insertion in the labor market, as well as mentoring by someone qualified to give the correct orientation, are essential for the rehabilitation of young female offenders forced to comply with socio-educational measures ("youngsters"). The objective of this project is to build a functional digital platform, along the lines of a social network focused on professional connections, where individuals and legal entities engaged with the cause of social inclusion ("volunteers") can offer job offerings and mentoring to the youngsters. The tool also has a part aimed at vocational guidance, with instructions for the preparation of a virtual curriculum vitae, and which associates tags ("tags") to the profile of the youngsters, corresponding to the interests and skills, according to data extracted from the construction of their profile. Based on the characteristics of volunteers and youngsters, as well as the tags associated with their profiles, the platform will seek to recommend connections, job offerings and mentoring, using artificial intelligence. The platform should have a layout that prioritizes usability, since the main audience will be young people, most of whom have little technical knowledge. 

Keywords: Inclusion; Youngsters; Socio-educational measures; Job; Rehabilitation.

## 1. INTRODUÇÃO 

A transformação de nossa sociedade passa obrigatoriamente pela inclusão de pessoas desprivilegiadas em todas as esferas de produção e pensamento, a fim de diminuir a desigualdade que debilita a grande maioria da população brasileira, oferecendo-lhes uma melhor condição de competição em uma corrida em que apenas uma minoria já nasce com vantagens na partida. 

Este esforço de inclusão, que precisa ser contínuo e abraçado por toda as camadas sociais, torna-se ainda mais necessário quando se trata de jovens - crianças e adolescentes, cujo caráter e personalidade ainda estão em formação, e que tão cedo já se envolveram em conflitos com a lei. Neste sentido, já comentaram Cella e Camargo[1]: 

Trata-se de ensinar para mostrar outra realidade, uma realidade em que o adolescente não precise lesar o próximo, como forma de lutar pela visibilidade e por melhores condições de vida. Render-se à violência, às prisões e aos maus tratos é também submeter-se à lógica de um sistema que impulsiona a violência, para que bem cedo esses jovens sejam afastados da sociedade que não os reconhece. 

Com o intuito de reabilitar jovens infratoras submetidas a medidas socioeducativas, o instituto Mundo Aflora busca efetivar a reintegração de jovens que já estiveram ou estão em privação de liberdade, encaminhando para oportunidades dentro e fora dos centros para fazer novas escolhas. 

Com base na premissa descrita nos primeiros parágrafos acima, e no trabalho realizado pelo Instituto Mundo Aflora, nasce a plataforma ConectAflora. 

### 1.1. Objetivos do Trabalho  

O objetivo do trabalho é a criação de uma plataforma online nos moldes de uma rede social voltada para conexões profissionais, onde pessoas (físicas e jurídicas) engajadas com a causa da inlcusão social ("voluntáries") possam oferecer vagas de trabalho e mentoria às jovens. 

A plataforma disponibilizará a construção de perfis, tanto para jovens quanto para voluntáries que desejem oferecer vagas de emprego ("vagas") e mentoria para este público específico. 

A ferramenta também conterá uma parte voltada à orientação vocacional, com instruções para a elaboração de um currículum vitae virtual, e que associe etiquetas ("tags") ao perfil das jovens, correspondentes aos interesses e habilidades, conforme dados extraídos da construção do perfil. 

Com base nas características de voluntáries e jovens, bem como nas tags associadas a seus perfis, a plataforma buscará realizar recomendação de conexões, vagas e mentorias, utilizando inteligência artificial. 

## 2. FUNDAMENTAÇÃO TÉCNICA 

Neste projeto serão abordados os tópicos de ciência de dados - aliada ao uso de tags para atribuição de recomendações, usabilidade e segurança da informação. 

### 2.1. Ciência de Dados e uso de tags para recomendações 

Um estudo conduzido em 2010 por Guy, Zwerdling, Ronen, Carmel e Uziel[2] demonstrou que o uso de tags pode ser muito eficiente para formulação de recomendações, pois estas se traduzem em melhores filtros para tópicos de interesse. 

Portanto, a fim de concretizar os objetivos da plataforma, a associação de tags foi o procedimento escolhido. 

### 2.2. Usabilidade  

A plataforma deverá contar com uma diagramação que priorize a usabilidade, visto que o público principal será a jovens, cuja maioria dispõe de pouco conhecimento técnico. 

### 2.3. Segurança da informação 

Considerando o volume e a sensibilidade dos dados que serão transitarão pela plataforma, normas de segurança de dados deverão ser aplicadas para garantir o cumprimento da legislação vigente.
Page Break
 
## 3. DESENVOLVIMENTO

A aplicação será construída no formato Progressive Web App (PWA), e utilizará arquitetura REST combinada a um framework frontend que garanta alta usabilidade. 

### 3.1. Progressive Web App (PWA) 

Progressive Web App (PWA) é uma metodologia de desenvolvimento de software que combina recursos de navegadores com os benefícios de aplicações para dispositivos móveis. 

Desta forma, buscamos garantir que a plataforma possa ser acessada com a devida fluidez por qualquer dispositivo, sem necessidade de instalação de aplicativo específico. 

### 3.2. Arquitetura REST 

Conforme mencionado por Thiago Berlitz Rondon, REST (Representational State Transfer ou Transferência de Estado Representacional) é estilo de arquitetura de software sobre um sistema operado em rede, que vê cada aplicação web como um conjunto de recursos, que representam um estado particular de um aplicativo. Quando você acessa este recurso, Rondon continua, você está transferindo o estado (conteúdo), e talvez alterando o seu estado [3]. 

A aplicação será baseada nesta modalidade de arquitetura, que será consumida pelo servidor de frontend. 

## REFERÊNCIAS  

[1]MACHADO CELLA, Silvana; POMPÊO DE CAMARGO, Dulce Maria. Trabalho pedagógico com adolescentes em conflito com a lei: feições da exclusão/inclusão Educação & Sociedade, vol. 30, núm. 106, enero-abril, 2009, pp. 281-299 Centro de Estudos Educação e Sociedade Campinas, Brasil. Disponível em https://www.redalyc.org/pdf/873/87313703014.pdf Acesso em 06/12/2020. 

[2]GUY, Ido; ZWERDLING, Naama; RONEN, Inbal; CARMEL, David; UZIEL, Erel. Social Media Recommendation based on People and Tags. IBM Research Lab, Haifa 31905, Israel, out. 2010. 

[3]RONDON, Thiago Berlitz. Arquitetura REST e o serviço web 'RESTful'. Publicado em 01/01/2010. Disponível http://sao-paulo.pm.org/pub/arquitetura-rest-e-o-servico-web-restful-. Acesso em 06/12/2020. 
