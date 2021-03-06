# Informações do Projeto
`NOME DO PROJETO`  

FinCare

`CURSO` 

......  Engenharia de Software ......

## Participantes

> Os membros do grupo são: 
> - Joana Morais
> - Maria Eduarda Amaral Muniz
> - Pedro Rocha
> - Andre Santana

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

-"Ganhos"(desejos, benefícios, expêriencias que amplificam sua experiência): 
Já tem uma certa estabilidade financeira; ter uma família;


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


## Wireframes


Login - Usuario tem a opcao de criar uma conta ou logar em uma ja
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


# Metodologia

> O processo de trabalho foi realizado por meio de reuniões semanais na Faculdade e na plataforma online do Google Meets. Nesses encontros compartilhamos ideias, dúvidas, certezas e suposições sobre o problema, mapeamos o
público alvo, fomos a campo fazer as entrevistas e com elas construímos as personas, identificando os problemas mais comuns e já pensando possíveis 
soluções para o problema. 
>

## Divisão de Papéis

 **Equipe de desenvolvimento:**
 - André Santana (Desenvolvedor Front End)
 - Maria Eduarda (Desenvolvedor Front End)
 - Joana Morais (Desenvolvedor Front End)
 - Pedro Rocha: (Desenvolvedor Front End)


## Ferramentas

| Ambiente  | Plataforma              |Link de Acesso |
|-----------|-------------------------|---------------|
|Processo de Design Thinkgin  | Miro |   | ![miro](https://miro.com/app/board/uXjVOBTKAwM=/) |
|Repositório de código | GitHub |  | ![GitHub](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2022-1-ti1-7924100-trabalho-gestao-financeira-t2g2)|
|Hospedagem do site | GitHub Pages |  XXXXX |  

>
> Miro, GitHub, google docs, PowerPoint, Figma, Canva, google drive, Google Meets. 
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

# Projeto da Solução

Nesta seção são apresentados os detalhes técnicos da solução criada pela equipe, tratando da Arquitetura da Solução, as estruturas de dados e as telas já implementadas.

**Template do site**

O template criado está disponível aqui no github e é composto pelos seguintes layouts: 

- Login e Cadastro
- Tela principal
- Tela de lembrete de pagamentos
- Tela de projeção de investimentos

**Login e Cadastro**

Tela que permite que o usuário se cadastre no site para acessá-lo ou que o permite se logar para ir para a página principal. 

![login](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2022-1-ti1-7924100-trabalho-gestao-financeira-t2g2/blob/master/docs/relatorio/images/login.jfif)

![cadastro](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2022-1-ti1-7924100-trabalho-gestao-financeira-t2g2/blob/master/docs/relatorio/images/cadastro.jfif)

**Tela Principal**

Tela que abrange todas as visualizações iniciais do site, o cadastro de recibos e despesas, tabela que ilustra as despesas e recibos durante os meses e mapeamento de gastos dividido em categorias.

![tela inicial](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2022-1-ti1-7924100-trabalho-gestao-financeira-t2g2/blob/master/docs/relatorio/images/tela%20inicial.jfif)

**Lembrete de Pagamentos**

Este layout é utilizado para exibir o cadastro de pagamentos futuros do usuário.

![lembrete](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2022-1-ti1-7924100-trabalho-gestao-financeira-t2g2/blob/master/docs/relatorio/images/lembrete.jfif)

**Cadastro de objetivos**

Local onde é cadastrado os investimentos e objetivos do usuário em um determinado período de tempo.

![objetivos](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2022-1-ti1-7924100-trabalho-gestao-financeira-t2g2/blob/master/docs/relatorio/images/objetivos.jfif)

## Tecnologias Utilizadas

> - Linguagens: Javascript, CSS, HTML
> - IDE: Visual Studio Code
> - Ferramentas: Extensão Live Server
> - Serviços Web: Github, Google Docs, Figma, Canva, Miro, Trello
> - Framework: Bootstrap

## Arquitetura da solução

**Componentes**

A solução implementada conta com os seguintes módulos:
Navegador - Interface básica do sistema 
Páginas Web - Conjunto de arquivos HTML, CSS, JavaScript e gráficos que implementam as funcionalidades do sistema.
Local Storage - armazenamento mantido no Navegador, onde são implementados bancos de dados baseados em JSON. São eles: 
Login - cadastrar e permitir o acesso do usuário ao site.
Lembretes - registra pagamentos futuros do usuário. 
Cadastros - guarda recibos e despesas do usuário.
Hospedagem - local na Internet onde as páginas são mantidas e acessadas pelo navegador. 

**Hospedagem**

O site utiliza a plataforma Github Pages como ambiente de hospedagem do site do projeto. 
A publicação do site no Github Pages é feita por meio do repositório do projeto, onde o Github Pages acessa esse repositório e o transforma em um site.

## Plano de Testes

| Caso de Teste  | CT-01 – Cadastro de usuário |
|-----------|-------------------------|
|Requisitos Associados  | RF-01 - Ao entrar na página de cadastro, o site deverá mostrar todos os inputs de cadastro, sendo eles, usuário, nome complero, email, senha e a confirmação de senha. RF-02 - Ao inserir os dados, deve haver uma confirmação de que o usuário foi cadastrado. |
|Objetivo do Teste  | Verificar se o usuário está sendo cadastrado corretamente.|
|Passos  | 1) Acessar o Navegador 2) Informar o endereço do Site 3) Acessar a página de cadastro 4) Inserir os dados de cadastro e confirmar|
|Critérios de Êxito  | Os dados devem ser armazenados em um JSON que irá guardar todas as informações do usuário. Esse JSON deverá ser salvo no Local Storage do navegador, para guardar as informações do usuário.|

| Caso de Teste  | CT-02 – Login do usuário |
|-----------|-------------------------|
|Requisitos Associados  | RF-03 - Após realizar o cadastro o usuário deverá realizar o login com os dados cadastrados.|
|Objetivo do Teste  | Verificar se o login está sendo realizado com sucesso e se caso o usuário inserir os dados errados, deverá retornar mensagem de erro.|
|Passos  | 1) Acessar o Navegador 2) Realizar o cadastro 3) Inserir os dados para login 4) Confirmar e realizar o login|
|Critérios de Êxito  | A página deverá consultar os arquivos em local storage para fazer a confirmação dos dados de login.|

| Caso de Teste  | CT-03 – Adicionar nova entrada ou saída |
|-----------|-------------------------|
|Requisitos Associados  | RF-04 – O usuário deverá clicar no botão de “Adicionar nova entrada ou saída”, inserir os dados e confirmar.|
|Objetivo do Teste  | Fazer a verificação se os dados estão sendo gravados e exibidos em tela.|
|Passos  | 1) Acessar a página de dashboard 2) Pressionar o botão de “Adicionar nova entrada ou saída” 3) Inserir os dados 4) Confirmar o envio|
|Critérios de Êxito  | Os dados serão armazenados em uma estrutura JSON, dentro do Local Storage do navegador. O programa deverá exibir a informação na área de saída ou entrada e realizar o cálculo de saldo final. O gráfico de mapeamento de gastos deverá ser atualizado, caso o cliente insira uma saída. E o gráfico de histórico também atualização.|

| Caso de Teste  | CT-04 – Editar/excluir entrada e saída |
|-----------|-------------------------|
|Requisitos Associados  | RF-05 – Após inserir a entrada ou saída, o usuário deverá ser capaz de editar ou excluir esses dados que ficam numa tabela.|
|Objetivo do Teste  | Verificar se os dados estão sendo removidos ou editados, e as informações atualizadas na tela.|
|Passos  | 1) Acessar a página de dashboard 2) Editar ou excluir algum dado da tabela 3) Se editado, inserir os novos dados 4) Confirmar o envio|
|Critérios de Êxito  | O dados inputados no arquivo JSON, deverão ser excluídos ou editados, a depender da opção selecionada. Os dados exibidos em tela de entrada e saída terão que ser atualizados após a confirmação de alteração.|

| Caso de Teste  | CT-05 – Lembrete de pagamentos |
|-----------|-------------------------|
|Requisitos Associados  | RF-06 – O usuário poderá incluir lembretes de pagamentos, com data, valor, nome e descrição.|
|Objetivo do Teste  | Verificar se o item é adicionado a tabela de lembretes.|
|Passos  | 1) Acessar a página de lembrete de pagamentos 2) Clicar no botão de incluir 3) Inserir os dados solicitados 4) Confirmar o envio|
|Critérios de Êxito  | O dados deverão ser armazenados em um JSON, e guardados no local storage do navegador.|

| Caso de Teste  | CT-06 – Simulador de investimentos |
|-----------|-------------------------|
|Requisitos Associados  | RF-07 – O usuário poderá simular investimentos com base nos dados inseridos por ele.|
|Objetivo do Teste  | Verificar se o gráfico de projeção de investimentos está sendo gerado corretamente.|
|Passos  | 1) Acessar a página de simulador de investimentos 2) Inserir os dados solicitados 3) Confirmar o envio  |
|Critérios de Êxito  | O dados serão processados e calculados, e após isso, irão inseridos no gráfico de projeção. |


## Registros de Testes

| Caso de Teste  | CT-01 – Cadastro de usuário |
|-----------|-------------------------|
|Objetivo do Teste  | Verificar se o usuário está sendo cadastrado corretamente.|
|Resultados  |![cadastro](https://raw.githubusercontent.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2022-1-ti1-7924100-trabalho-gestao-financeira-t2g2/6dba0628ece12dd71431fa217725b1b63487a1d7/docs/relatorio/images/WhatsApp%20Image%202022-07-08%20at%2021.55.15.jpeg) ![confirmacao](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2022-1-ti1-7924100-trabalho-gestao-financeira-t2g2/blob/master/docs/relatorio/images/WhatsApp%20Image%202022-07-08%20at%2021.55.15%20(1).jpeg) |

| Caso de Teste  | CT-02 – Login do usuário |
|-----------|-------------------------|
|Objetivo do Teste  | Verificar se o login está sendo realizado com sucesso e se caso o usuário inserir os dados errados, deverá retornar mensagem de erro.|
|Resultados  | ![nome da imagem](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2022-1-ti1-7924100-trabalho-gestao-financeira-t2g2/blob/master/docs/relatorio/images/login%20(1).jpeg) ![nome da imagem](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2022-1-ti1-7924100-trabalho-gestao-financeira-t2g2/blob/master/docs/relatorio/images/login%20(2).jpeg) |

| Caso de Teste  | CT-03 – Adicionar nova entrada ou saída |
|-----------|-------------------------|
|Objetivo do Teste  | Fazer a verificação se os dados estão sendo gravados e exibidos em tela.|
|Resultados  | ![nome da imagem](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2022-1-ti1-7924100-trabalho-gestao-financeira-t2g2/blob/master/docs/relatorio/images/entrada%20(1).jpeg)  ![nome da imagem](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2022-1-ti1-7924100-trabalho-gestao-financeira-t2g2/blob/master/docs/relatorio/images/entrada%20(2).jpeg)|

| Caso de Teste  | CT-04 – Editar/excluir entrada e saída |
|-----------|-------------------------|
|Objetivo do Teste  | Verificar se os dados estão sendo removidos ou editados, e as informações atualizadas na tela.|
|Resultados  | ![nome da imagem](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2022-1-ti1-7924100-trabalho-gestao-financeira-t2g2/blob/master/docs/relatorio/images/edtexxc%20(1).jpeg) ![nome da imagem](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2022-1-ti1-7924100-trabalho-gestao-financeira-t2g2/blob/master/docs/relatorio/images/edtexxc%20(2).jpeg)|

| Caso de Teste  | CT-05 – Lembrete de pagamentos |
|-----------|-------------------------|
|Objetivo do Teste  | Verificar se o item é adicionado a tabela de lembretes.|
|Resultados  | ![nome da imagem](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2022-1-ti1-7924100-trabalho-gestao-financeira-t2g2/blob/master/docs/relatorio/images/Lembrete.jpeg) |

| Caso de Teste  | CT-06 – Simulador de investimentos |
|-----------|-------------------------|
|Objetivo do Teste  | Verificar se o gráfico de projeção de investimentos está sendo gerado corretamente.|
|Resultados  | ![nome da imagem](https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2022-1-ti1-7924100-trabalho-gestao-financeira-t2g2/blob/master/docs/relatorio/images/Simulador.jpeg) |


# Referências

MORBECK, Amandina. Pesquisa mostra descontrole financeiro de metade dos brasileiros. Você e seu dinheiro. 05. fev. 2020. Disponível em: https://voceeseudinheiro.com.br/pesquisa-mostra-descontrole-financeiro-de-metade-dos-brasileiros/. Acesso em: 24 abr. 2022;
