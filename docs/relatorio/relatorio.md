# Informações do Projeto
`TÍTULO DO PROJETO`  

Pets Hunter

`CURSO` 

Curso de Engenharia de Software 

## Participantes

> Os membros do grupo são: 
> - Luiz Gustavo Mendes Santos            
> - Amanda Moura de Souza	
> - João Gabriel Perez Monteiro	         
> - Lucas Carvalho Peres 	
> - Pedro Lucas Machado Santos         

# Estrutura do Documento

- [Informações do Projeto](#informações-do-projeto)
  - [Participantes](#participantes)
- [Estrutura do Documento](#estrutura-do-documento)
- [Introdução](#introdução)
  - [Problema](#problema)
  - [Objetivos](#objetivos)
  - [Justificativa](#justificativa)
  - [Público-Alvo](#público-alvo)
- [Especificações do Projeto](#especificações-do-projeto)
  - [Personas e Mapas de Empatia](#personas-e-mapas-de-empatia)
  - [Histórias de Usuários](#histórias-de-usuários)
  - [Requisitos](#requisitos)
    - [Requisitos Funcionais](#requisitos-funcionais)
    - [Requisitos não Funcionais](#requisitos-não-funcionais)
  - [Restrições](#restrições)
- [Projeto de Interface](#projeto-de-interface)
  - [User Flow](#user-flow)
  - [Wireframes](#wireframes)
- [Metodologia](#metodologia)
  - [Divisão de Papéis](#divisão-de-papéis)
  - [Ferramentas](#ferramentas)
  - [Controle de Versão](#controle-de-versão)
- [**############## SPRINT 1 ACABA AQUI #############**](#-sprint-1-acaba-aqui-)
- [Projeto da Solução](#projeto-da-solução)
  - [Tecnologias Utilizadas](#tecnologias-utilizadas)
  - [Arquitetura da solução](#arquitetura-da-solução)
- [Avaliação da Aplicação](#avaliação-da-aplicação)
  - [Plano de Testes](#plano-de-testes)
  - [Ferramentas de Testes (Opcional)](#ferramentas-de-testes-opcional)
  - [Registros de Testes](#registros-de-testes)
- [Referências](#referências)


# Introdução

## Problema

  De a cordo com o IBGE e pelo Instituto Pet Brasil, em 2018 no Brasil foram contabilizados mais de 139 milhões de animais de estimação, entre eles estão gatos, cachorros, aves, peixes, repteis e pequenos mamíferos. Esse número tende a crescer todos os anos e consequentemente, com tantos animais, é previsível que alguns deles acabem se perdendo ao fugir de suas residenciais. Esse número aumenta ainda mais em datas comemorativas, onde fogos de artifícios espantam os animais e fazem com que eles fujam.<br><br>
  Outro ponto a ser ressaltado é o fato de que muitos donos abandonam seus animais. De acordo com o Instituto Pet Brasil, cerca de 172.1 mil animais de estimação são abandonados sob os cuidados de ONGs, e a Associação 	do Animais, Pro Anima, registrou nos três primeiros meses de 2022 no Distrito Federal um crescimento de 60% na quantidade de pessoas que querem se desfazer de seus animais. Todos esses fatores em conjunto ocasionam em milhares de animais abandonados nas ruas. 

## Objetivos

  “Pets Hunter” é um sistema que visa achar uma solução para substituir ferramentas que não tem esse propósito específico, como o Twitter, rede social onde muitos usuários acabam divulgando postagens sobre animais perdidos. Esse sistema facilitaria aos donos encontrarem seus animais. O sistema vai integrar um espaço para registro e divulgação de animais perdidos, com pesquisa baseada nas características dos animais e na localização onde foi perdido. É de extrema importância que o sistema seja simples e intuitivo, podendo ser utilizado por indivíduos de qualquer idade.

## Justificativa

  Com o problema em mente é possível analisar que muitos indivíduos que perdem seus animais, acabam recorrendo as redes sociais para auxiliar na busca. Existem páginas nessas redes sociais como, facebook ou twitter, que são dedicas exclusivamente a divulgação de animais perdidos. O maior problema é que em certos casos em meio a uma enxurrada de posts muitas postagens ficam perdidas e não são visualizadas. Esse tipo de busca não tem os filtros adequados que facilitam na hora de procurar um animal. Com sorte esse método leva alguns donos a acharem seus animais, mas quando isso acontece, já existem centenas de postagens que estão a meses ou anos sem atualizações.<br><br>
  Por esta razão desenvolveu-se a ideia de criar um sistema feito exclusivamente para procurar animais com paramentos e filtros adequados, garantindo que uma postagem não desaparecerá em meio as muitas outras.


## Público-Alvo

  A partir dos dados coletados com as entrevistas conseguimos traçar dois perfis principais de usuários. Cada perfil está relacionado a um momento diferente: um que perdeu o animal e outro que achou o animal.<br><br>
  Usuário que perdeu o pet: Os usuários que perdem os animais não estão acostumados com a criação e divulgação desse problema, deixando de lado informações importantes sobre os animais. A idade é outro fator que varia muito entre esses usuários mostrando que o sistema tem que ser simples para que todos os usuários possam utilizar.<br><br>
   Usuário que encontrou o pet: Os usuários que acham os pets, que se solidarizam e abrigam os animais, por outro lado já estão mais acostumados a ajudá-los da melhor maneira possível. Geralmente eles possuem mais experiencia na hora de criar postagens e colocar as informações mais pertinentes.

 
# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Contexto.md"> Documentação de Contexto</a></span>

## Personas e Mapas de Empatia
1. **Livia**: tem 25 anos, trabalha como floriculturista, passa a maior parte do tempo na sua floricultura cuidado das flores, isso leva ela a vestir sempre um avental e utilizar luvas, carregando flores para todos os lados. Lívia acaba encontrando muitos animais perdidos em sua floricultura, ela planeja usar o serviço de pets perdidos para registrar os animais que encontra e achar seus reais donos.<br>
2. **Ricardo**: tem 42 anos, trabalha como escritor, assa a maior parte do tempo em sua casa tentando escrever livros, sempre vestindo seu pijama e carregando seu notebook para todo lado. vive em casa ocupado com seu gato, ele utilizaria esse serviço caso um dia perdesse seu animal.<br>
3. **Francisca**: tem 65 anos, trabalha em um bar, trabalha em seu bar na beira da estrada e é onde passa mais tempo, lá ela veste sempre sua roupa casual e carrega um pano para limpar o balcão de bebidas.Quando não esta no bar passa o tempo com sua família em sua casa. Francisca usaria o serviço de animais perdidos para divulgar os animais que aparecem no seu bar, na tentativa de achar seus donos.<br>

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Livia | Um sistema para encontrar animais perdidos          | Registrar o desaparecimento do meu cachorro ou tentar achar alguém que tenha o resgatado            |
|Roberto     | Um sistema para encontrar animais perdidos           | Registrar os animais que eu resgato e abrigo em minha casa |


## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Registro de pets	Alta| ALTA | 
|RF-002| Divulgação no site	Alta | ALTA |
|RF-003| Filtro de localização| ALTA | 
|RF-004| Registro de pets abrigados| ALTA |
|RF-005| Área de contato | MÉDIA | 
|RF-006| Cadastro de voluntários.| MÉDIA |
|RF-007| Pesquisa baseada nas descrições dos pets.| MÉDIA | 
|RF-008| Postagens apagam depois de um tempo   | MÉDIA |
|RF-009| Local para divulgação de recompensas nas postagens	Baixa | BAIXA | 
|RF-0010|Mapa com localização de veterinários e petshops| BAIXA |
|RF-0011| Divulgação dos desaparecimentos em redes sociais| BAIXA | 
|RF-0012| Dicas para encontrar os animais | BAIXA |


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivo móvel | MÉDIA | 
|RNF-002| O sistema deve ser eficiente, mesmo em hardware de baixo desempenho  |  MÉDIA | 
|RNF-003 Banco de dados para armazenar dados dos animais e usuários |  MÉDIA | 


## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |


# Projeto de Interface

Uma das principais necessidades do projeto é de que a interface seja intuitiva por conta da variedade de idade dos usuarios. Com isso mente, foi desenhada uma interface simples e *clean* para atender esse requisito.

## User Flow

......  INCLUA AQUI O DIAGRAMA COM O FLUXO DO USUÁRIO NA APLICAÇÃO ......

> Fluxo de usuário (User Flow) é uma técnica que permite ao desenvolvedor
> mapear todo fluxo de telas do site ou app. Essa técnica funciona
> para alinhar os caminhos e as possíveis ações que o usuário pode
> fazer junto com os membros de sua equipe.
>
> **Links Úteis**:
> - [User Flow: O Quê É e Como Fazer?](https://medium.com/7bits/fluxo-de-usu%C3%A1rio-user-flow-o-que-%C3%A9-como-fazer-79d965872534)
> - [User Flow vs Site Maps](http://designr.com.br/sitemap-e-user-flow-quais-as-diferencas-e-quando-usar-cada-um/)
> - [Top 25 User Flow Tools & Templates for Smooth](https://www.mockplus.com/blog/post/user-flow-tools)
>
> **Exemplo**:
> 
> ![Exemplo de UserFlow](images/userflow.jpg)


## Wireframes

......  INCLUA AQUI OS WIREFRAMES DAS TELAS DA APLICAÇÃO COM UM BREVE DESCRITIVO ......

> Wireframes são protótipos das telas da aplicação usados em design de interface para sugerir a
> estrutura de um site web e seu relacionamentos entre suas
> páginas. Um wireframe web é uma ilustração semelhante ao
> layout de elementos fundamentais na interface.
> 
> **Links Úteis**:
> - [Ferramentas de Wireframes](https://rockcontent.com/blog/wireframes/)
> - [Figma](https://www.figma.com/)
> - [Adobe XD](https://www.adobe.com/br/products/xd.html#scroll)
> - [MarvelApp](https://marvelapp.com/developers/documentation/tutorials/)
> 
> **Exemplo**:
> 
> ![Exemplo de Wireframe](images/wireframe-example.png)


# Metodologia

......  COLOQUE AQUI O SEU TEXTO ......

> Nesta parte do documento, você deve apresentar a metodologia 
> adotada pelo grupo, descrevendo o processo de trabalho baseado nas metodologias ágeis, 
> a divisão de papéis e tarefas, as ferramentas empregadas e como foi realizada a
> gestão de configuração do projeto via GitHub.
>
> Coloque detalhes sobre o processo de Design Thinking e a implementação do Framework Scrum seguido
> pelo grupo. O grupo poderá fazer uso de ferramentas on-line para acompanhar
> o andamento do projeto, a execução das tarefas e o status de desenvolvimento
> da solução.
> 
> **Links Úteis**:
> - [Tutorial Trello](https://trello.com/b/8AygzjUA/tutorial-trello)
> - [Gestão ágil de projetos com o Trello](https://www.youtube.com/watch?v=1o9BOMAKBRE)
> - [Gerência de projetos - Trello com Scrum](https://www.youtube.com/watch?v=DHLA8X_ujwo)
> - [Tutorial Slack](https://slack.com/intl/en-br/)

## Divisão de Papéis

......  COLOQUE AQUI O SEU TEXTO ......

> Apresente a divisão de papéis e tarefas entre os membros do grupo.
>
> **Links Úteis**:
> - [11 Passos Essenciais para Implantar Scrum no seu Projeto](https://mindmaster.com.br/scrum-11-passos/)
> - [Scrum em 9 minutos](https://www.youtube.com/watch?v=XfvQWnRgxG0)


## Ferramentas

......  COLOQUE AQUI O SEU TEXTO - SIGA O EXEMPLO DA TABELA ABAIXO  ......

| Ambiente  | Plataforma              |Link de Acesso |
|-----------|-------------------------|---------------|
|Processo de Design Thinkgin  | Miro |  https://miro.com/XXXXXXX | 
|Repositório de código | GitHub | https://github.com/XXXXXXX | 
|Hospedagem do site | Heroku |  https://XXXXXXX.herokuapp.com | 
|Protótipo Interativo | MavelApp ou Figma | https://figma.com/XXXXXXX | 

>
> Liste as ferramentas empregadas no desenvolvimento do
> projeto, justificando a escolha delas, sempre que possível.
> 
> As ferramentas empregadas no projeto são:
> 
> - Editor de código.
> - Ferramentas de comunicação
> - Ferramentas de diagramação
> - Plataforma de hospedagem
> 
> O editor de código foi escolhido porque ele possui uma integração com o
> sistema de versão. As ferramentas de comunicação utilizadas possuem
> integração semelhante e por isso foram selecionadas. Por fim, para criar
> diagramas utilizamos essa ferramenta por melhor captar as
> necessidades da nossa solução.
> 
> **Links Úteis - Hospedagem**:
> - [Getting Started with Heroku](https://devcenter.heroku.com/start)
> - [Crie seu Site com o HostGator](https://www.hostgator.com.br/como-publicar-seu-site)
> - [GoDady](https://br.godaddy.com/how-to)
> - [GitHub Pages](https://pages.github.com/)

## Controle de Versão

......  COLOQUE AQUI O SEU TEXTO ......

> Discuta como a configuração do projeto foi feita na ferramenta de
> versionamento escolhida. Exponha como a gerência de tags, merges,
> commits e branchs é realizada. Discuta como a gerência de issues foi
> realizada.
> A ferramenta de controle de versão adotada no projeto foi o
> [Git](https://git-scm.com/), sendo que o [Github](https://github.com)
> foi utilizado para hospedagem do repositório `upstream`.
> 
> O projeto segue a seguinte convenção para o nome de branchs:
> 
> - `master`: versão estável já testada do software
> - `unstable`: versão já testada do software, porém instável
> - `testing`: versão em testes do software
> - `dev`: versão de desenvolvimento do software
> 
> Quanto à gerência de issues, o projeto adota a seguinte convenção para
> etiquetas:
> 
> - `bugfix`: uma funcionalidade encontra-se com problemas
> - `enhancement`: uma funcionalidade precisa ser melhorada
> - `feature`: uma nova funcionalidade precisa ser introduzida
>
> **Links Úteis**:
> - [Tutorial GitHub](https://guides.github.com/activities/hello-world/)
> - [Git e Github](https://www.youtube.com/playlist?list=PLHz_AreHm4dm7ZULPAmadvNhH6vk9oNZA)
> - [5 Git Workflows & Branching Strategy to deliver better code](https://zepel.io/blog/5-git-workflows-to-improve-development/)
>
> **Exemplo - GitHub Feature Branch Workflow**:
>
> ![Exemplo de Wireframe](images/Github-Workflow.png)

# **############## SPRINT 1 ACABA AQUI #############**


# Projeto da Solução

......  COLOQUE AQUI O SEU TEXTO ......

## Tecnologias Utilizadas

......  COLOQUE AQUI O SEU TEXTO ......

> Descreva aqui qual(is) tecnologias você vai usar para resolver o seu
> problema, ou seja, implementar a sua solução. Liste todas as
> tecnologias envolvidas, linguagens a serem utilizadas, serviços web,
> frameworks, bibliotecas, IDEs de desenvolvimento, e ferramentas.
> Apresente também uma figura explicando como as tecnologias estão
> relacionadas ou como uma interação do usuário com o sistema vai ser
> conduzida, por onde ela passa até retornar uma resposta ao usuário.
> 
> Inclua os diagramas de User Flow, esboços criados pelo grupo
> (stoyboards), além dos protótipos de telas (wireframes). Descreva cada
> item textualmente comentando e complementando o que está apresentado
> nas imagens.

## Arquitetura da solução

......  COLOQUE AQUI O SEU TEXTO E O DIAGRAMA DE ARQUITETURA .......

> Inclua um diagrama da solução e descreva os módulos e as tecnologias
> que fazem parte da solução. Discorra sobre o diagrama.
> 
> **Exemplo do diagrama de Arquitetura**:
> 
> ![Exemplo de Arquitetura](images/arquitetura-exemplo.png)


# Avaliação da Aplicação

......  COLOQUE AQUI O SEU TEXTO ......

> Apresente os cenários de testes utilizados na realização dos testes da
> sua aplicação. Escolha cenários de testes que demonstrem os requisitos
> sendo satisfeitos.

## Plano de Testes

......  COLOQUE AQUI O SEU TEXTO ......

> Enumere quais cenários de testes foram selecionados para teste. Neste
> tópico o grupo deve detalhar quais funcionalidades avaliadas, o grupo
> de usuários que foi escolhido para participar do teste e as
> ferramentas utilizadas.
> 
> **Links Úteis**:
> - [IBM - Criação e Geração de Planos de Teste](https://www.ibm.com/developerworks/br/local/rational/criacao_geracao_planos_testes_software/index.html)
> - [Práticas e Técnicas de Testes Ágeis](http://assiste.serpro.gov.br/serproagil/Apresenta/slides.pdf)
> -  [Teste de Software: Conceitos e tipos de testes](https://blog.onedaytesting.com.br/teste-de-software/)

## Ferramentas de Testes (Opcional)

......  COLOQUE AQUI O SEU TEXTO ......

> Comente sobre as ferramentas de testes utilizadas.
> 
> **Links Úteis**:
> - [Ferramentas de Test para Java Script](https://geekflare.com/javascript-unit-testing/)
> - [UX Tools](https://uxdesign.cc/ux-user-research-and-user-testing-tools-2d339d379dc7)

## Registros de Testes

......  COLOQUE AQUI O SEU TEXTO ......

> Discorra sobre os resultados do teste. Ressaltando pontos fortes e
> fracos identificados na solução. Comente como o grupo pretende atacar
> esses pontos nas próximas iterações. Apresente as falhas detectadas e
> as melhorias geradas a partir dos resultados obtidos nos testes.


# Referências

......  COLOQUE AQUI O SEU TEXTO ......

> Inclua todas as referências (livros, artigos, sites, etc) utilizados
> no desenvolvimento do trabalho.
> 
> **Links Úteis**:
> - [Formato ABNT](https://www.normastecnicas.com/abnt/trabalhos-academicos/referencias/)
> - [Referências Bibliográficas da ABNT](https://comunidade.rockcontent.com/referencia-bibliografica-abnt/)
