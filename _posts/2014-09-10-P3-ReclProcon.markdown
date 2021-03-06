---
layout: project
title:  "Reclamações Procon"
subtitle: "Um serviço de busca e visualização intuitiva para que os cidadãos possam se orientar em um processo de decisão de compra"
date:   2014-09-10 17:49:49
categories: app
description: "O projeto possibilita que as queixas feitas às empresas sejam filtradas pelo gênero dos consumidores e pelo estado de atendimento das reclamações pelo fornecedor. Com apenas um clique no gráfico ou no texto é possível ativar o filtro, que mostrará os gráficos correspondentes à porcentagem total de reclamações."
authors: ["luiz_volso", "adriano_alves", "marcos_russ", "daniel_ishigaki", "thiago_takeshi"]
technologies: "CSS3, HTML5, Javascript"
authors_tolltip: "Luis Volso <br> Adriano Alves <br> Marcos Russ <br> Daniel Ishigaki <br> Thiago Takeshi"
github: https://github.com/lhvolso/ReclamacoesProcon
final_version: http://www.reclamacoesprocon.com.br/
status: Lançado em 08/05/2012
raw_data: http://dados.gov.br/dataset/cadastro-nacional-de-reclamacoes-fundamentadas-procons-sindec
thumb: "3_reclamacoesprocon_thumb.png"
background: "3_reclamacoesprocon_1022x606.png"
---

##Contextualização

O [Reclamações Procon](http://www.reclamacoesprocon.com.br/) é um dos projetos premiados no [1º Concurso de Aplicativos para Dados Abertos](http://www.w3c.br/Noticias/CerimoniaDePremiacaoDo1ConcursoDeDadosAbertosW3cmj), iniciativa realizada pelo escritório do W3C no Brasil e o Ministério da Justiça em novembro de 2012. A ideia era criar aplicações que proporcionassem uma melhor experiência de visualização de empresas reclamadas no Procon, auxiliando os consumidores em sua tomada de decisão.

Os [dados](http://dados.gov.br/dataset/cadastro-nacional-de-reclamacoes-fundamentadas-procons-sindec) foram disponibilizados pelo Cadastro Nacional de Reclamações Fundamentadas de 2011 realizado pelos 26 Procons estaduais e 232 Procons municipais, que por sua vez estão integrados ao Sistema Nacional de Informações de Defesa do Consumidor, o Sindec.

Frente a 32 equipes inscritas no concurso, o Reclamações Procon conquistou o 2º lugar no pódio junto com o projeto [Reclamações Br](http://reclamacoes-br.herokuapp.com/#/). Em primeiro lugar ficou o aplicativo [Reputação S/A](http://reputacao-sa.org/), em terceiro e quarto lugares ficaram, respectivamente, as aplicações [ProAnálise](http://www.proanalise.co.nf/) e [Proconfie](http://proconfie.vod.dcc.ufmg.br/).

Desenvolvido por [Luiz Volso](http://github.com/lhvolso), [Adriano Alves](http://github.com/adrianoalima), [Marcos Huss](https://twitter.com/marcoshuss), Daniel Ishigaki e Thiago Takeshi, a proposta do Reclamações Procon é ser um serviço de busca e visualização intuitiva para que os cidadãos possam se orientar em um processo de decisão de compra. Basta digitar o nome de uma empresa para que a ferramenta retorne rapidamente com os resultados.

De forma dinâmica, o site Reclamações Procon possibilita que as queixas feitas às empresas sejam filtradas pelo gênero dos consumidores (masculino e feminino) e pelo estado de atendimento das reclamações pelo fornecedor (atendidas e não atendidas). Com apenas um clique no gráfico ou no texto é possível ativar o filtro, que mostrará os gráficos correspondentes à porcentagem total de reclamações.

Para um dos integrantes da equipe, Luiz Volso, a experiência foi bastante compensadora. “Foi o primeiro concurso que participamos e já conseguimos a segunda colocação. Todo o reconhecimento que tivemos pela comunidade e, principalmente, por termos proporcionado à população um maior acesso às informações publicas, valeu todo o esforço aplicado nesse projeto.”

O desenvolvedor também explica que não ficou surpreendido com o resultado das visualizações e do cruzamento de informações. “Na verdade os dados mostraram uma realidade que eu já esperava, muitas reclamações das grandes empresas, principalmente na parte de cobrança indevida, um dado interessante foi a faixa etária dos reclamantes, a maioria deles está na faixa de 31 a 60 anos”.Como o próprio site do projeto informa, a motivação para desenvolver o Reclamações Procon surgiu em uma reunião após um dia normal de aula.

Os estudantes do curso de especialização em Padrões Web, da Universidade Tecnológica Federal do Paraná, decidiram participar do concurso para aplicar os conhecimentos adquiridos como uma forma de fixar o conteúdo aprendido nas disciplinas. Com uma equipe com diferentes habilidades e tamanha dedicação, o resultado não poderia ser outro.

##Desafios Envolvidos

Os desafios apontados são os mesmos diagnosticados pela equipe do Reputação S/A: “O formato que os dados foram fornecidos fez com que o desenvolvimento atrasasse, pois foi necessário a importação das informações para um banco de dados relacional”, ressalta Luiz Volso.

Outra dificuldade enfrentada pela equipe do Reclamações Procon foi a falta de padronização na identificação das empresas. “Como o sistema é todo descentralizado, cada órgão que recebe as reclamações cadastra o nome da empresa de forma diferente. Para iniciar o projeto precisamos fazer uma grande correção nos dados, o que tomou bastante o nosso tempo”, lamenta o desenvolvedor.

Para que o Reclamações Procon possa ser continuado, é necessário não somente a atualização da base de dados disponibilizada pelo Cadastro Nacional de Reclamações Fundamentadas, que não é atualizada desde 2012, como também a uniformização dos dados, pois há uma enorme variação das informações disponibilizadas em 2012 quando comparadas com os dados de 2011 utilizados no aplicativo, sendo crucial a adaptação de uma série de novos elementos para o projeto.

##Linguagens e tecnologias utilizadas:

Para a camada de conteúdo foi utilizado [HTML5](http://dev.w3.org/html5/html-author/); para a camada de apresentação visual o [CSS](http://www.w3.org/Style/CSS/Overview.en.html); e para a camada de comportamento (funcionalidades dos gráficos) o [JavaScript](http://www.crockford.com/javascript/javascript.html).







