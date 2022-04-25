# Informações do Projeto
`NOME DO PROJETO`  

......  Projeto de Gestão Financeira ......

`CURSO` 

......  Engenharia de Software ......

## Participantes

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

Em um mundo onde as informações são processadas rapidamente e os resultados são cobrados em contextos imediatos após ações executadas, é natural de se esperar que muitas tomadas de decisões relacionadas à organização financeira se percam no caminho. Não faltam informações, dicas, tutoriais e ensinamentos sobre gestão monetária na world wide web, no entanto, cerca de 48% dos consumidores brasileiros negativaram seu nome — é o que mostra um levantamento realizado em 2019 pela Confederação Nacional de Dirigentes Lojistas (CNDL) e pelo Serviço de Proteção ao Crédito (SPC).

Um dos motivos listados para esse descontrole financeiro na referida pesquisa é, por exemplo, a falta de anotações para entradas e saídas de gastos. Esquecer-se de anotar o valor pago em um “cafezinho” pode, aparentemente, parecer irrisório em certo contexto, mas se essa anotação não tornar-se um hábito constante, todo o mapeamento financeiro de um indivíduo pode vir a calhar. 

Logo, por meio de técnicas elaboradas pela engenharia de software, os membros da equipe pretendem construir uma aplicação online que solucione, ao menos em parte, o grande problema que acomete a vida de tantos consumidores. O presente trabalho documenta a construção dessa aplicação, que tem como meta garantir atributos funcionais, eficientes, seguros e de usabilidade ao usuário.


## Problema
As dúvidas sanadas nos portais de buscas não seriam suficientes para o entendimento de uma situação tão ampla. Se era preciso mais, conhecer a pessoa real por trás desse transtorno é o primeiro desafio. Com a ajuda da “Matriz CSD”, o grupo selecionou possíveis questões, situações, experiências e panoramas que geralmente acometem indivíduos no universo da gestão financeira. E foi por meio desse levantamento e também por entrevistas realizadas em campo, que o grupo obteve um relativo entendimento da situação. 

O grupo necessitou de uma ferramenta para pulverizar tais perguntas. Logo, para que a pesquisa tivesse alcance, a coleta dessas informações foi realizada por meio da plataforma Google Fóruns na qual o usuário, em uma única página selecionava, as respostas nas quais mais se pautava o seu contexto financeiro.

Dentre as perguntas disponibilizadas para esse público, 90% das respostas afirmaram que esse indivíduo em questão tem renda e que cerca de 70% não realizam nenhum tipo de mapeamento financeiro. Desse universo, aproximadamente 56% das pessoas relatam ter poupança ou algum tipo de dinheiro guardado, enquanto cerca de 44% afirmou não fazer esse tipo de aplicação. 

Também foi questionado no fórum se esse usuário em potencial recebeu algum tipo de educação financeira ao longo de sua vida e cerca de 80% das respostas afirmaram não ter recebido educação monetária em sua formação.

Esse panorama fez os membros da equipe acreditarem que as dores referentes à gestão financeira desses indivíduos era causada justamente pela falta de mapeamento - sejam eles sobre quaisquer rótulos, desde gastos e despesas, e até mesmo por ignorarem o fator esquecimento quando se trata de tomar notas sobre tais valores. Por consequência, a ausência desse registro pode resultar em um descontrole sobre o patrimônio que cada indivíduo constrói dia após dia.

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

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |



# Projeto de Interface



A interface do nosso programa tem como objetivo ser bem simples e intuitiva, com palavras chaves que levam a pessoa ao que ela busca, como por exemplo esta interface que representa uma previa da página inicial do app. 

![front](https://user-images.githubusercontent.com/67551515/165001352-1c62beb8-4f85-4024-aaa7-0d8a684076aa.png)














Que mostra algumas informações básicas como o saldo em conta da pessoa, e dinheiro de entrada( que ganhou) e de saida( que gastou).caso a pessoa queira ver o mapeamento de suas despesas ela pode clicar e sera direcionado a escolher a opção que mais a agrada como demonstrarei no user flow e no wireframe.


## User Flow



![New User Flow](https://user-images.githubusercontent.com/99201419/165001522-71aebd26-cd1d-43ea-93b5-1eea360eb286.png)

> **Links Úteis**:
> - [User Flow: O Quê É e Como Fazer?](https://medium.com/7bits/fluxo-de-usu%C3%A1rio-user-flow-o-que-%C3%A9-como-fazer-79d965872534)
> - [User Flow vs Site Maps](http://designr.com.br/sitemap-e-user-flow-quais-as-diferencas-e-quando-usar-cada-um/)
> - [Top 25 User Flow Tools & Templates for Smooth](https://www.mockplus.com/blog/post/user-flow-tools)
>
> **Exemplo**:
> 
> ![Exemplo de UserFlow](images/userflow.jpg)


## Wireframes


Login.Usuario tem a opcao de criar uma conta ou logar em uma ja
existente


![Captura de tela 2022-04-24 204745](https://user-images.githubusercontent.com/99201419/165001767-2b7eb7aa-11ce-4e0b-a29c-43b3a027a550.png)


Pagina principal do app. Pagina inicial do app, aqui o usuario encontra as infirmações mais basicas do app, o qual ele tem 5 opções: mapeamento de despesas, investimentos,simulação, configuraçoes e perfil.


![front](https://user-images.githubusercontent.com/67551515/165001352-1c62beb8-4f85-4024-aaa7-0d8a684076aa.png)


Mapeamento de despesas. Onde o usuario pode ver o dinheiro de entrada ou o de saida, e saber as informaçoes sobre suas despesas.


![Captura de tela 2022-04-24 204835](https://user-images.githubusercontent.com/99201419/165001785-a5e0c6e8-07e2-42c3-abea-d2861806c6da.png)


Investimentos. Onde o usuario pode ver suas informações sobre investimentos.


![Captura de tela 2022-04-24 204937](https://user-images.githubusercontent.com/99201419/165001820-a25ef609-93a7-458c-8c13-36fda9b73efb.png)


Simulação. Onde o usuario pode fazer simulacoes sobre gastos, investimentos ou gastos.


![Captura de tela 2022-04-24 205033](https://user-images.githubusercontent.com/99201419/165001855-ca5387e5-ac9d-4133-aee7-e89962598876.png)


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
