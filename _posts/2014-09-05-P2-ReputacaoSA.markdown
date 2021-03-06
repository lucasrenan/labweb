---
layout: project
title: "Reputação S/A"
subtitle: "Ferramenta para a visualização de dados de empresas reclamadas no Procon."
date: 2014-09-05 17:49:49
categories: app
description: "Ferramenta para a visualização de dados de empresas reclamadas no Procon."
authors: ["thiago_bueno", "vitor_baptista", "leonardo_tartari"]
technologies: "Ruby, Google Refine, Mongo DB, Javascript, HTML, CSS3"
authors_tolltip: "Thiago Bueno <br> Vitor Baptista <br> Leonardo Tartari"
github: https://github.com/dataviz/reputacao-sa.org
final_version: http://reputacao-sa.org/
status: Lançado em 08/05/2014
raw_data: http://dados.gov.br/dataset/cadastro-nacional-de-reclamacoes-fundamentadas-procons-sindec
background: "2_reputacao_s_a_1022x606.png"
---
##Contextualização

O 1º Concurso de Aplicativos para Dados Abertos, ação conjunta do escritório do [W3C no Brasil](www.w3c.br) e Ministério da Justiça, trabalhou com a base de dados do Cadastro Nacional de Reclamações Fundamentadas (PROCONS – Sindec) para que desenvolvedores pudessem criar ferramentas que facilitassem a orientação dos cidadãos na hora de efetuar uma compra. Além disso, essa iniciativa teve como objetivo promover a cultura do acesso à informação e da abertura de dados, incentivando uma maior participação social dos cidadãos em temas públicos.

O concurso, lançado em novembro de 2012, teve como aplicativo vencedor o [Reputação S/A](http://reputacao-sa.org/), ferramenta para a visualização de dados de empresas reclamadas no Procon. Desenvolvido por [Thiago Bueno](http://tbueno.com/), Leonardo Tartari e [Vitor Baptista](http://vitorbaptista.com/), o Reputação S/A tem como proposta ajudar o consumidor a ter mais entendimento sobre a base de dados por meio de interfaces e gráficos de fácil interpretação.

Com uma simples navegação, é possível explorar de forma bastante intuitiva as principais informações sobre as empresas campeãs em reclamações. Ainda, a aplicação oferece um guia que facilita a instalação para diferentes sistemas operacionais como o Android ou iPhone. Apesar dos downloads terem caído após os meses que seguiram o concurso, o aplicativo ainda possui dezenas de acessos semanais na versão feita para desktop, que hoje corresponde a 90% dos acessos.

Para o programador Thiago Bueno, o concurso foi uma ótima experiência. “Passamos por praticamente todos os desafios clássicos de projetos de dados como: coleta, organização, agrupamento e visualização de uma grande quantidade de informação. Nós gostamos muito desse tipo de iniciativa, pois além de praticar e aprender, também conseguimos criar algo com valor informativo no final”.

O desenvolvedor lembra que um dos dados que chamou a atenção da equipe foi a comprovação de que empresas ligadas à telefonia móvel eram de fato as líderes absolutas de reclamação. “Algo que também nos saltou aos olhos foi a quantidade de reclamações por cobrança indevida por essas empresas, fazendo com que esse seja, disparado, o maior motivo de transtornos dos consumidores”.

Ao todo foram 32 equipes inscritas. Em segundo lugar ficaram as equipes do [Reclamações Procon](http://www.reclamacoesprocon.com.br/) e do [Reclamações Br](http://reclamacoes-br.herokuapp.com/#/). Em terceiro lugar ficou o aplicativo web [Pro Análise](http://www.proanalise.co.nf/) e em quarto o [Proconfie](http://proconfie.vod.dcc.ufmg.br/) que teve menção honrosa.

##Desafios envolvidos

Os principais desafios para a realização da aplicação e para mantê-la atualizada recaem sobre a própria base de dados, que além de não estar atualizada desde 2012, também apresenta incongruência nas informações disponibilizadas. Thiago Bueno explica que os conglomerados varejistas foram mal agrupados na base de dados. “As reclamações de empresas como Submarino e Americanas.com foram registradas como [B2W](https://pt.wikipedia.org/wiki/B2W_Digital), que na verdade surgiu da fusão das mesmas. O mapeamento de nome fantasia e razão social também não estava claro o suficiente em muitos casos”.

Como o [Procon](http://pt.wikipedia.org/wiki/Fundação_Procon) não está presente em todas as cidades de um estado, sendo os dados das reclamações disponibilizados apenas onde esse órgão atua, Thiago Bueno ressalta que uma fonte interessante para cruzamento de dados seria as agências de reclamação online como o [Reclame Aqui](http://www.reclameaqui.com.br/), onde as reclamações não chegam a ser levantadas no Procon, mas online e diretamente com as empresas.

Para o futuro, há ainda outras formas interessantes de se explorar esse projeto, como fazendo o agrupamento por setores da indústria, o que facilitaria a comparação entre empresas do mesmo mercado, entretanto só faz sentido esse esforço caso a base de dados fosse constantemente renovada e a equipe fizesse o esforço de manter o aplicativo sempre atualizado.

##Linguagens e tecnologias utilizadas 

Para a limpeza dos dados foi utilizado [Ruby](https://www.ruby-lang.org/en/) e [Google Refine](https://code.google.com/p/google-refine/). No servidor, [Rails](http://rubyonrails.org/) e banco de dados [MongoDB](http://www.mongodb.org/). Para a visualização, foram utilizados [HTML](http://dev.w3.org/html5/html-author/), [CSS](http://www.w3.org/Style/CSS/Overview.en.html) e [JavaScript](http://www.crockford.com/javascript/javascript.html).


