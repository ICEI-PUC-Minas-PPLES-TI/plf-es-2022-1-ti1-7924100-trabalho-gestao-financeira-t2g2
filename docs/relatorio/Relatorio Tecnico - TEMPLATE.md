# Informações do Projeto
`TÍTULO DO PROJETO`  

......  COLOQUE AQUI O SEU TEXTO ......

`CURSO` 

......  COLOQUE AQUI O SEU TEXTO ......

## Participantes

......  COLOQUE AQUI O SEU TEXTO ......

> Inclua a lista dos membros da equipe com seus nomes completos.
>
> Os membros do grupo são: 
> - Joana Morais
> - Maria Eduarda Amaral Muniz
> - Pedro Rocha
> - Andre Santana
> - Henrique Mascarenhas
> - Eduardo Puig
> - Gustavo Chagas

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
Cada dia que passa, a informação tem se tornado o ativo mais importante na vida de pessoas e das organizações. Informações precisas, imparciais e obtidas no momento exato são fundamentais para se orientar nesse mundo de grandes incertezas. //teste


## Problema

Pela configuração da Matriz sobre as Certezas, Suposições e Dúvidas feita pelo referido grupo do projeto, foi selecionada uma série de perguntas sobre finanças pessoais e organização financeira. Por meio das respostas acreditou-se que haveria um maior entendimento sobre como poderia ser realizada a aplicação web. Contudo, o grupo necessitou de uma ferramenta para pulverizar todas essas perguntas de maneira aberta para o público e que este, em modo anônimo caso preferisse, pudesse respondê-las. Para realizar tal pesquisa foi utilizada a plataforma Google Fóruns.

As perguntas disponibilizadas para este público retornaram que, dentre as pessoas que têm renda, cerca de 70% não realiza nenhum tipo de mapeamento financeiro. Desse universo, aproximadamente 56% das pessoas afirmou ter algum tipo de poupança ou dinheiro guardado, enquanto cerca de 44% afirmou não fazer esse tipo de aplicação. Também foi questionado no fórum se esse usuário em potencial recebeu algum tipo de educação financeira e por volta de 80% das respostas afirmou não ter recebido educação monetária ao longo de sua formação.

Apesar de alguns usuários relatarem a segurança de ter uma poupança com rendimentos, o panorama geral nos fez acreditar que as dores referentes à gestão financeira desses indivíduos era causada justamente pela falta de mapeamento - sejam esses mapeamentos sobre quaisquer rótulos de gastos, despesas, entradas e saídas monetárias. Por consequência, sua ausência pode resultar em um descontrole sobre o patrimônio que cada indivíduo constrói ao longo de sua vida.

## Objetivos

O objetivo geral deste trabalho é a criação de uma aplicação web que apresente ferramentas de fácil uso e que permita a visualização do comportamento financeiro do usuário por meio de gráficos, tabelas e projeções.

Como objetivos específicos, podemos ressaltar:
- Entrada para o usuário declarar recibos e despesas;
- Mapeamento dos gastos. Exemplo: 30% alimentação, 30% investimento, etc;
- Notificar o usuário quando este excede o limite de gastos;
- Notificar o usuário quando têm contas para pagar ou quando está negativado em relação a alguém ou alguma instituição.

## Justificativa

A motivação para a resolução do problema foi o desejo de traduzir o problema real do usuário por meio do uso de ferramentas matemáticas que podem ser implementadas no corpo do software. Além disso, a própria interação do grupo com indivíduos reais, que apresentam problemas vividos em seu cotidiano e, por isso, buscam uma resolução prática e rápida para suas respectivas dores. Além do questionário realizado pela plataforma Google Fóruns, realizou-se também entrevistas de campo para que se fossem obtidas informações cada vez mais detalhadas desses problemas, o que contribuiu para o entendimento geral da problemática.

De fato, existe já disponível no mercado uma série de apps e plataformas - inclusive feitas pelas próprias instituições bancárias -, mas que, aparentemente, não solucionaram o problema de gestão dos indivíduos que responderam à pesquisa realizada pelo fórum. 

## Público-Alvo

Embora todas as pessoas possam se beneficiar de soluções apresentadas pelo software em questão, o foco deste trabalho está no público que tenha renda e está em busca constante de consolidar seu patrimônio, ou que já tenha este patrimônio consolidado e busca somente organizá-lo de maneira concisa e com o detalhamento matemático necessário.

Desta forma, estabeleceu-se como público-alvo desta solução pessoas que se identifiquem com qualquer orientação de gênero, nas idades entre 25 e 40 anos, com carreiras já consolidadas ou não, e que fazem uso frequente de computadores e dispositivos móveis. Tal indivíduo estaria apto para se atualizar e detalhar seus sonhos e aspirações por meio de um efetivo controle financeiro e, por consequência, colocar planos e metas em prática.
 
# Especificações do Projeto

Foi por meio de reuniões semanais que se deu a personificação do problema. Nos primeiros encontros debateu-se sobre quem seriam os possíveis usuários da referida aplicação e se era necessário que esse usuário tivesse uma renda para utilizar a plataforma. É importante ressaltar que dúvidas e suposições foram fundamentais para o desenvolvimento da pesquisa e coleta de dados. Vale ressaltar também que, além do formulário criado, os membros da equipe foram a campo para conhecer esse usuário em potencial no corpo a corpo, com o objetivo de entender sua rotina, seus sonhos, aspirações, anseios e comportamentos financeiros apresentados por eles. 

Logo, é possível afirmar que a coleta de dados online e em em campo foi fundamental para que as histórias e problemas reais relatados pelos contribuidores tomassem corpo em três personas distintas. Estas, o time acredita, são as três grandes figuras centrais, o grande foco e inspiração para o referido trabalho.

## Personas e Mapas de Empatia


>Persona 1:

-Nome: Davi

-Idade: 31 anos

-Trabalho: Área de TI

-Perfil: Reservado, Pão duro, Organizado, Antenado.

-Desejos:Casa própria, Renda alta, Liberdade financeira, Suporte financeiro para a família, Empreender.

-roblemas: Controle do tempo, organizar compromissos, não atingir objetivos de carreira ainda, falta de tempo.


Mapa de empatia:

-Sente: imediatista; 
-O que realmente importa? Dinheiro na conta, sucesso no trabalho;
-O que mais preocupa? Não ter reservas financeiras no futuro;
-Anseios: Casa própria;
-Inspirações: Mark Zuckerberg, Warren Buffet, Wendell Carvalho. 

-"Dores"(necessidades,problemas que enfrenta, frustrações, obstáculos): 
Controle do tempo, organizar compromissos, não atingir objetivos de carreira ainda, falta de tempo.

-"Ganhos"(desejos, benefécios, expêriencias que amplificam sua experiência): 
Melhor ambiente de trabalho, salário elevado, trabalhar onde quiser, já tem posição elevada no trabalho.


>Pesona 2:

-Nome: Ana 

-Idade: 26 anos 

-Trabalho: Comerciante

-Desejos: Independência financeira, Qualidade de vida, Bem estar familiar, Rodar o mundo.

-Perfil: Comunicativa, Extrovertida, Esforçada,  Organizada.

-Problemas: Dívidas, falta de tempo; sempre sem dinheiro; não conseguir ajudar a família financeiramente, burnout.


Mapa de empatia:

-Sente: medo do futuro, presa à rotina;
-O que realmente importa? independência financeira, qualidade de vida;
-O que mais preocupa? controle de gastos, bem estar familiar;
-Anseios: mudar de emprego, subir de cargo;
-Inspirações: Janis Joplin, Clarice Lispector, Machado de Assis. 

-"Dores"(necessidades, problemas que enfrenta, frustrações, obstáculos): 
Dívidas, falta de tempo, sempre sem dinheiro, não conseguir ajudar a família financeiramente, burnout.

-"Ganhos"(desejos, benefécios, expêriencias que amplificam sua experiência): 
Rodar o mundo, socializar, sua boa comunicação a emancipa.


>Persona 3:

-Nome: Patrícia 

-Idade: 40 anos 

-Trabalho: Funcionária pública 

-Perfil: Organizada, Preocupada, Atenta, Dócil,  Atenciosa.

-Desejos: Quitar as dívidas, Dar um futuro bom para os filhos, Ter uma boa aposentadoria. 

-Problemas: Dívidas, parcelas do financiamento, ainda não ter imóvel próprio, sustentar a educação dos filhos.

Mapa de empatia: 

-Sente: independência financeira, medo do futuro;
-O que realmente importa? bem estar familiar, qualidade de vida, uma boa aposentadoria;
-O que mais preocupa? quitar as dívidas, futuro dos filhos;
-Anseios: plano de carreira;
-Inspirações: seus pais, filhos, Simone de Beauvoir.

-"Dores"(necessidades,problemas que enfrenta, frustrações, obstáculos): 
Dívidas, parcelas do financiamento, ainda não ter imóvel próprio, sustentar a educação dos filhos,

-"Ganhos"(desejos, benefécios, expêriencias que amplificam sua experiência): 
Já tem uma certa estabilidade financeira; ter uma família;


> Relacione as personas identificadas no seu projeto e os respectivos mapas de empatia. Lembre-se que 
> você deve ser enumerar e descrever precisamente e de forma
> personalizada todos os principais envolvidos com a solução almeja. 
> 
> Para tanto, baseie-se tanto nos documentos disponibilizados na disciplina
> e/ou nos seguintes links:
>
> **Links Úteis**:
> - [Persona x Público-alvo](https://flammo.com.br/blog/persona-e-publico-alvo-qual-a-diferenca/)
> - [O que é persona?](https://resultadosdigitais.com.br/blog/persona-o-que-e/)
> - [Rock Content](https://rockcontent.com/blog/personas/)
> - [Hotmart](https://blog.hotmart.com/pt-br/como-criar-persona-negocio/)
> - [Mapa de Empatia](https://resultadosdigitais.com.br/blog/mapa-da-empatia/)
> - [Como fazer um mapa de empatia - Vídeo](https://www.youtube.com/watch?v=JlKHGpVoA2Y)
> 
> 
> **Exemplo de Persona**
> 
> ![Exemplo de Persona](imaages/../images/persona.png)
> 
> Fonte: [Como criar uma persona para o seu negócio](https://raissaviegas.com.br/como-criar-uma-persona/)


## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Usuário do sistema  | Organizar os meus gastos           | Administrar o meu salário              |
|Usuário do sistema  | Controlar minhas finanças          | Não gastar dinheiro impulsivamente     |
|Usuário do sistema  | Controle de gastos com compras     | Limitar meus gastos mensais            |

> Apresente aqui as histórias de usuário que são relevantes para o
> projeto de sua solução. As Histórias de Usuário consistem em uma
> ferramenta poderosa para a compreensão e elicitação dos requisitos
> funcionais e não funcionais da sua aplicação. Se possível, agrupe as
> histórias de usuário por contexto, para facilitar consultas
> recorrentes à essa parte do documento.
>
> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Categorização de gastos                 | ALTA  | 
|RF-002| Relembrar datas de pagamento            | MÉDIA |
|RF-003| Gráficos e tabelas                      | MÉDIA |
|RF-004| Possibilade de criar objetivos          | MÉDIA |
|RF-005| Notificação de excesso de gastos        | ALTA  |
|RF-006| Declaração de recibos e despesas        | ALTA  |

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| Interface colorida e intuitiva  | MÉDIA | 
|RNF-002| Facilidade de uso               | ALTA  |
|RNF-003| O site será publicado no GitHub | MÉDIA |
|RNF-004| O site deverá ser responsivo    | ALTA  |

> Com base nas Histórias de Usuário, enumere os requisitos da sua
> solução. Classifique esses requisitos em dois grupos:
>
> - [Requisitos Funcionais (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
>   correspondem a uma funcionalidade que deve estar presente na
>   plataforma (ex: cadastro de usuário).
>
> - [Requisitos Não Funcionais (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
>   correspondem a uma característica técnica, seja de usabilidade,
>   desempenho, confiabilidade, segurança ou outro (ex: suporte a
>   dispositivos iOS e Android).
>
> Lembre-se que cada requisito deve corresponder à uma e somente uma
> característica alvo da sua solução. Além disso, certifique-se de que
> todos os aspectos capturados nas Histórias de Usuário foram cobertos.
> 
> **Links Úteis**:
> 
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)


## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |


> Enumere as restrições à sua solução. Lembre-se de que as restrições
> geralmente limitam a solução candidata.
> 
> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)


# Projeto de Interface

......  COLOQUE AQUI O SEU TEXTO DE INTRODUÇÃO ......

> Apresente as principais interfaces da solução. Discuta como 
> foram elaboradas de forma a atender os requisitos funcionais, não
> funcionais e histórias de usuário abordados nas [Especificações do
> Projeto](#especificações-do-projeto).

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
