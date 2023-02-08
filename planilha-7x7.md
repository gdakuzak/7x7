# Para preencher experiências:

Para níveis 3 e 4, comece pelas evidências. As evidências devem mencionar a `situação` (projeto e momento) onde os `exemplos ocorreram`, com objetivo de demonstrar `consistência`.

Para atingir consistência, espera-se cerca de `~6 meses de atuação`.

- `Nível inicial: Nível exploratório` -  esperado que a pessoa esteja no momento de absorção de conhecimento, não é necessário marcar o item.
- `Nível 1: Nível aprendiz, ou nível de domínio teórico` - esperado que a pessoa tenha profundidade teórica (de ponta a ponta)  sobre o que está sendo pedido.
- `Nível 2: Nível de capacidade, ou nível de conhecimento prático` - esperado que a pessoa tenha consistência em praticar o que está sendo pedido, com suporte.
- `Nível 3: Nível de proficiência` - esperado que a pessoa tenha consistência em praticar o que está sendo pedido sem nenhum suporte.
- `Nível 4: Nível expert` - esperado que a pessoa tenha experiência em praticar o que está sendo pedido em cenários complexos. Cenários válidos a serem usados de exemplo abaixo:
  - 1 - Escala - Os seus exemplos demonstram que você atuou em maior escala (Múltiplos times ou projetos)
  - 2 - Adversidade - Os seus exemplos demonstram que você atuou em cenários adversos (cliente ou situação complicada e/ou atenuada, requerendo energia extra em comunicação e alinhamentos ou escalações frequentes)
  - 3 - Complexidade técnica - Os seus exemplos demonstram atuação em uma tecnologia diferente da que habitualmente trabalha, que seja peculiar, com poucos profissionais especialistas, e/ou muito nova no mercado, com nenhum ou pouquíssimo suporte externo e interno."

___

## Coding Excellence: Codifico de forma clara e objetiva utilizando as melhores práticas

### L3

@todo - Pensar como exemplificar.

### L4

___

## Coding Excellence: Avalio e defino padrões para codificação garantindo que sejam seguidos por todo o time

### L3

    (Empresa: Yahp | 2019-2020) Defini o modelo a ser usado pelo time que estava iniciando os projetos como dependency pattern, onde temos dependencia entre as entidades model, repositorio, serviço e contrato.
    
    (Coca - Noctis) O projeto estava sem code pattern definidos, então colocamos um conceito de Clean Code no código que definimos para o processo como um todo, utilizando modelo, repositorio e useCase para refatorar os códigos.

### L4

___

## Coding Excellence: Investigo e aplico diferentes métodos de análise, identificando e solucionando problemas técnicos.

### L3

    (Dafiti) Precisamos procurar uma sequencia de chaves que eram utilizadas para realizar a alteração na página principal e das categorias. Utilizei localmente o Log do Yii para trazer essas chaves e também utilizei o debugger para ajudar a encontrar em que ponto cada uma das chaves eram chamadas.
    
    (Dafiti) Utilizamos uma aplicação chamada Vegeta para pegar os erros que aconteciam quando disparavamos muitas requisições na aplicação Hawk. Utilizamos tambem ferramentas de APM (Instana/New Relic) e também o Grafana para identificar, a partir de métricas, possíveis erros.
    
    (Paketa) Para entender o que era chamado na aplicação utilizamos debugger e também fizemos muitos testes utilizando console.log em pontos que já tinhamos testado no Postman.
    
    (Coca  - Noctis) Utilizamos desde testes de unidade, dump and die (dd), Logs e também resultados de API para validar os dados.

### L4

___

## Coding Excellence: Identifico e implemento/oriento a melhoria de pontos prioritarios do codigo, como desempenho ou manutenibilidade

### L3

### L4

___

## Coding Excellence: Identifico a necessidade e construo PoCs no meu contexto quando necessário, fazendo uso de frameworks ou linguagens modernas

### L3

    (Dafiti) Para levantar hipóteses sobre uma nova solução para o novo web, realizei uma POC para ver a viabilidade de fazer um frontend baseado no ExpressJS, uma vez que o framework utilizado (Yii) está desatualizado e o upgrade seria inviavel, vendo a viabilidade de comunicação com memached e comunicação com a entrega do catálogo.
    
    (Dafiti) Fiz uma POC para verificar a disponibilidade das imagens do S3 da Dafiti e aprensentá-los na tela e validar se a URL estava válida, pois estavamos recebendo alertas e chamado sobre a indiponibilidade dessas imagens. Utilizei NodeJS, para fazer um teste de viabilidade para a entrega dessas imagens em outra tecnologia. Foi identificado que apenas 25 das 1000 imagens realmente estavam com problemas, e passamos a verificar as possibilidades de como entregar melhor para o SEO / usuários as imagens.
    
    (Paketa) Fiz uma POC para criação de dados gerados aleatoriamente no banco de dados mongo utilizando Laravel (Faker), depois de indentificarmos que o cliente tinha muito problema para fazer a geração de dados, dependendo quase que exclusivamente de uma geração pela QA ou copiando os dados ja existentes. Conseguimos fazer a entrega de criação de novas propostas e pagamentos. O próximo passo é gerar novas empresas e novos usuários.

    (Coca - Noctis) Realizei uma POC para entender se poderiamos utilizar uma lib de React poderia ser a solução para implementação de busca, ordenação e filtros específicos para aquela tabela.

    (Coca - Noctis) Realizei POC para comprar se conseguimos acessar e processar alguns dados em JSON, que estava dentro de um bucket S3 (AWS). Teste foi bem sucessidido, o que acabou evoluindo para um código que fazemos processamento assíncrono.

### L4

___

## Coding Excellence: Apoio a melhoria do código de outras pessoas colaboradoras, fornecendo feedback por meio de revisões de código

### L3
    
    (Empresa: Yahp | 2019-2020) Eu realizava revisão de códigos e funcionalidade dos desenvolvedores juniores e também de estagiários, explicando sobre correções que deveriam ser feitas para que o código ficasse mais fácil de entender.

    (Paketa) Entre os membros do time, antes de passar pela revisão do cliente, faziamos revisão dos códigos onde revisão principalmente a logica do sistema, uma vez que o projeto trazia dificuldade por trabalhar com gerção de cobranças.

    (Coca - Noctis) Eu ficava responsável por fazer Code Review dos membros do time, apontando algumas melhorias de escrita, entrega ou lógica.

### L4

___

## Continuous Delivery: Defino e configuro um ambiente de Integração Contínua com todas as suas práticas/fases

### L3

### L4

___

## Continuous Delivery: Defino ou customizo a estratégia de versionamento de código adequada ao meu contexto, e a utilizo corretamente

### L3

### L4

___

## Continuous Delivery: Defino e automatizo o pipeline de entrega adequado para o meu contexto, e garanto que o time o utilize corretamente

### L3

### L4

___

## Continuous Delivery: Automatizo o provisionamento de ambientes através de ferramentas

### L3

### L4

___

## Continuous Delivery: Identifico métricas técnicas ou de negócio e implanto o monitoramento das mesmas, dando ciência delas ao cliente ou ao time.

### L3

### L4

___

## Continuous Delivery: Desenho e aplico arquiteturas em processos que habilitam a entrega contínua e a testabilidade da solução

### L3

### L4

___

## Quality: Defino e implanto a estratégia de teste automatizado para garantia da qualidade

### L3

    (Coca - Noctis) Todas as features entregues nos ambientes, tinham um nível de testes unitários ou testes funcionais na URI da API para garantir a entrega dos dados e das funcionalidade de forma mais assertiva. 

### L4

___

## Quality: Planejo e executo testes adicionais (acessibilidade, desempenho ou segurança), interpretando os resultados e comunicando sugestões de próximos passos

### L3

### L4

___

## Quality: Participo e/ou lidero o assunto qualidade no meu escopo através de governança dos processos

### L3

### L4

___

## Quality: Defino metas de qualidade e apoio o time a alcançá-las usando o resultado das ferramentas de análise do código

### L3

### L4

___

## Quality: Planejo e faço testes exploratórios / manuais de forma eficiente e garantindo a execução do fluxo completo.

### L3

### L4

___

## Quality: Planejo e executo os planos de ação oriundos da análise de causas-raízes melhorando a qualidade

### L3

### L4

___

## Architecture & Design: Desenho e valido em fórum técnico soluções / arquiteturas baseadas no negócio e sob restrições técnicas

### L3

    (Dafiti) Fiz proposta de arquitetura para o novo web, saindo de um conceito monolito e indo pra um conceito de API REST, separando as responsabilidades de back-end e front-end. Para o back-end, escolhemos manter a mobile-api como entrega do sistema, fazendo adaptações e modificações necessárias para trazer informações necessárias para as homes, página de produto e também do catalogo. Para o front-end, pensei em utilizar o NextJS por ser baseado em React e também por ter muitas feature que poderiam ser utilizadas para tratar o SEO e também receber algumas informações do CMS (BOB). As propostas que foram feitas

### L4

___

## Architecture & Design: Proponho soluções prevendo efeitos colaterais, defendendo-a e explicando as razões de decisões técnicas ao cliente e lideranças

### L3

    (Dafiti) Fui responsável por realizar uma proposta de um novo web, desenhando uma solução técnica trocando o monolito para um API RESTful e uma das preocupações foi ter uma solução de CMS para deixar o time de marketing. Sugeri colocar o Prismic para o CMS ou a criação de modelos dentro do BOB. Sugeri também fazer uma limpeza de tags dentro do Dynamic Yield: retirando aquilo que não é mais usado, retirar códigos permanentes e colocar no Alice e, se fosse necessário, refatorar códigos que precisam ficar no DY. Outra dificuldade levantada é ter 2 projetos para o front e sugeri refatorar para um framework responsivo (TailwindCSS) e retirando o projeto de front existente que separa Web e Mobile. As sugestões foram passadas para o SL, para o time, coordenador, gerente e PO, para verificar a viabilidade desse projeto.

### L4

___

## Architecture & Design: Incentivo e garanto que todo o time faça uso das melhores práticas de desenvolvimento de software

### L3

### L4

___

## Architecture & Design: Realizo o refinamento técnico absorvendo rapidamento o contexto do cliente e transfiro o conhecimento para o time durante o desenvolvimento

### L3

    (Paketa - 2022) Eu puxo o refinamento técnico do time para fazer um detalhamento técnico mais preciso e ter um caminho mais claro para o PO e o time. Durante o refinamento e planning, levanto duvidas e hipoteses de solução e já validando a viabilidade das soluções levando para o PO para que ele nos ajude nas tomadas de decisão, sempre vendo se existe mais de uma alternativa e considerando a que é a mais assertiva para a solução.

### L4

___

## Architecture & Design: Crio e mantenho roadmap em colaboração com os gestores, gerindo dívidas técnicas e priorizando itens técnicos no roadmap do projeto

### L3

### L4

___

## Architecture & Design: Elaboro uma estratégia para modernização tecnológica da plataforma do cliente, validando com as lideranças e comunicando-a efetivamente ao cliente

### L3
    
    (Dafiti) Elaborei uma estratégia de melhoria das dependencias do GTM, Dynamic Yield e CMS para verificar quais eram as tags que precisarem ser refatoradas ou poderiam estar no código estático do Alice. Foi realizada priorização dos dados do CMS e removidas tags antigas do Dyniamic Yield; A porposta foi validada e enviada ao coordenador e ao PO do contexto, para que entendessem as mudanças e quais os problemas e soluções da atividade.
    
    (Dafiti) Elaborei uma estratégia de subtituição do Alice para um novo web, retirando o monolito que existe para uma estrutura de serviço api + frontend, utilizando o NextJS para a entrega do front e utitlizando a mobile-api (API já existente) como back-end. A estratégia era substituir primeiramente a página do produto, verificando como se comportaria a nova tecnologia com muitos acessos e novos recursos, e ir substituindo cada uma dos tipos de página (home pages, catalogo, paginas institucionais, entre outras). Foi feita call com o meu SL, Coodernador, PO, Gerente de Engenharia e com o time sobre a estratégia.

### L4

___

## Process: Colaboro ativamente durante reuniões de planejamento incentivando o meu time ao compromisso coletivo com as estimativas

### L3

    (Paketa) No contexto do cliente que temos uma visão mais simplificada do produto, levantamos durante a planning os riscos e possíveis soluções que podemos ter durante a sprint, levando principalmente ao PO nossas preocupações. Na sprint 4 tivemos uma acertividade maior.

### L4

___

## Process: Identifico e implanto melhorias de processo usando como base métricas coletadas da operação

### L3

### L4

___

## Process: Explico efetivamente todo o contexto / história do projeto, sempre me valendo de métricas durante a apresentação

### L3

    (Dafiti) No time de Finding, após o mês de Julho/2021, comecei a ajudar o onboarding do time, mostrando e conversando com os novos contratos, como era o contexto e quais os desafios do contexto. Como, por exemplo, as integrações com o Hawk e Fisherman para a indexação dos produtos.

    (Paketa) Durante algumas reuniões com o cliente, expliquei o contexto que estamos inseridos e explicando de que maneira as atividades foram feitas e de que maneira elas poderiam ter algum impacto na operação. Exemplo: Explicação das entidades para o Rodrigues na entrega do dia 29/06.

### L4

___

## Process: Utilizo as ferramentas de acordo com o processo definido pelo time dando plena visibilidade das minhas atividades e do time

### L3

### L4

___

## Process: Monitoro, priorizo e alimento o backlog ajudando o time a ter conhecimento claro das próximas tarefas, técnicas ou não

### L3

    (Paketa) Ajudei a quebrar a atividade mais complexa que estava na sprint, gerando uma quebra na atividade e tarefas no backlog de débitos técnicos relacionado a criação de script para criação do campo dateReference na entidade billet, necessária para mostrar os boletos na área do RH.

### L4

___

## Process: Mobilizo o time e participo de agendas para melhoria contínua, criando uma lista de ações futuras utilizando métricas de processo como referência.

### L3

### L4

___

## Teamwork: Dou feedback de forma efetiva (com exemplos) aos membros do time, dando visibilidade dessa ação aos líderes

### L3

### L4

___

## Teamwork: Identifico e formo sucessores, diminuindo as dependências de pessoas específicas ou para viabilizar crescimento.

### L3

    (Dafit) Na saída do time de Finding para o time de Optimization, passei meus conhecimentos para o time que ficou em Finding, me disponibilizando para ajudar a qualquer momento, especialmente para a Nathalia (Dafiti) na qual seria a mais antiga do contexto, passando os possíveis e principais gaps da área.

    (Paketa) Na finalização do contrato, foi feito offboarding com o cliente, onde passei os processos descritos em documentos e pendencias, juntamente com o PO.

### L4

___

## Teamwork: Planejo e viabilizo a capacitação de todo o time para cobrir eventuais lacunas de conhecimento técnico identificados

### L3

### L4

___

## Teamwork: Contagio todo o time pelo exemplo e postura ao encarar desafios de forma positiva fazendo-os enxergar as eventuais oportunidades

### L3

### L4

___

## Teamwork: Incentivo, através do exemplo, revisões técnicas (ex: Solution Review) canalizando a experiência coletiva na produção de uma nova solução de melhor qualidade

### L3

### L4

___

## Teamwork: Compartilho conhecimentos regularmente em canais apropriados aumentando o conhecimento do time, área ou comunidade

### L3

### L4

___

## Soft skills: Comunico de forma efetiva e negocio propostas e soluções técnicas com o cliente

### Status: Validado

### L3

    (Yahp) Fiz uma reunião com o cliente onde reportou para mim que estava tendo dificuldades com a geração de arquivos XML que era enviado para o cliente. Fiz uma proposta de apartar essa parte do código em um novo repositório onde poderiamos trabalhar um refactor daquilo que era feito e trabalhar a performance desses dados. A proposta foi aceita e o projeto foi feito em 3 semanas, melhorando a performance da entrega dos arquivos de 4-5 horas, para 63 minutos.

    (Paketa) Fiz uma reunião com o cliente, onde era necessário criar um status intermediario a proposta de PAGO e NÃO PAGO, uma vez que existiria um pagamento com status de não pago, porém um boleto já foi gerado para o cliente. Fiz a proposta de colocar um status virtual de PENDENTE, onde o status seria uma solução lógica entre o campo billet e o status UNPAID. A prosposta foi aceita pelo cliente e documentada.

### L4

___

## Soft skills: Entrego de forma consistente tarefas sob minha responsabilidade sendo reconhecido como alguém que se pode contar

### L3

    (Empresa: Yahp | 2019-2020) Durante um dos projetos, tive que fazer uma integração com o sistema de geração de notas fiscais, onde havia uma data do início da utilização, pois era quando virava os contratos dos clientes, retirada do serviço de geração de notas do financeiro e também o início do mês, onde começariamos a gerar notas fiscais e faturas. A atividade foi entregue 6 dias antes dos previsto, tendo tempo habil para fazer testes e validar as integrações. O cliente me informou que gostou da entrega e estava o que ele esperava e elogiou o comprometimento com a gerencia, dando margem para eles fazerem as revisões necessárias.

    (Paketa) Comprometimento com a entrega do MVP do cliente Paketa, onde tivemos atividades críticas realizando baterias de testes e bugfix durante a semana da entrega. Ajudei na entrega, apoiando meus colegas de trabalho, tanto no review, quanto no apoio de pensar como as atividades devem ser feitas. Fui reconhecido pelo Phellipe e pelo Angelo pela ajuda nas explicações e ajuda para finalizar a sprint. Entrega foi feita 1 dia antes do prazo final.

### L4

___

## Soft skills: Me comunico de forma eficaz e escalo qualquer tipo de necessidade em tempo hábil evitando que ocorram crises no projeto

### L3

    (Paketa) Identifiquei, durante a análise para execução automática da geração de boletos, que poderia haver ids de fundos diferentes dentro de uma array, me levando a questionar se poderia ter uma alteração, errônea ou não desses fundos. Verifiquei no backoffice que esses ids poderiam ser diferentes para o cliente, dependendo do política de empréstimo. Diante desta fragilidade, informei ao PO imediatamente para verificar se existia alguma regra de negócio ou se isso seria um GAP no desenvolvimento do sistema. O PO verificou com a PM e constatou que se tratava de um GAP do sistema e que este afetava 57 clientes.

### L4

___

## Soft skills: Construo e mantenho credibilidade com o cliente, time e liderança

### L3

    (Dafiti) Fiz um refinamento em conjunto com o time, SL e também coordenadores para fazer a troca do Alice por uma outra solução em front-end para melhorar nossa entrega no front para o cliente final e também ganhar confiança na hora de fazer o código, uma vez que teriamos um melhor cenário de código e menos medo de fazer o código. A iniciativa foi muito bem recebida, gerando discussões e feedbacks positivos com o cliente pela iniciativa, gerando confiança dos colaboradores Dafiti/CI&T para ter melhores entregar.

    (Paketa) Fiquei responsável juntamente com o PO por realizar refinamentos técnicos com o time do cliente (Avengers e Cockpit) para identificação de oportunidades de melhorias na entrega do backend e definir soluções a serem implementadas e descritas nas histórias e o cliente gostava dessa integração, pois dava mais segurança para a implementação do front-end pelo cliente e algumas vezes alteravamos o desenvolvimento atendendo especificações que foram solicitadas pelo cliente. Ganhamos confiança da PM e da liderança pois tivemos entregar muito assertivas e nos momentos de dúvidas do cliente, mostramos o ownership da solução e responder todas as questões para o cliente.
    
    (Paketa) Na finalização do projeto, foi solicitado pelo cliente uma reunião para alinhamento das atividades na qual passei, em detalhes, as histórias pendentes e juntamente com o PO, fizemos um alinhamento preciso, expondo necessidades do sistema, melhorias que precisariam ser implementas e já tinham sido identificadas. A pedido do cliente, documentamos com detalhes os endpoints desenvolvidos para enviar para o PM que ficou responsavel do projeto e mesmo com a finalização do contrato o cliente, ele se mostrou muito grato e surpreso pelo conhecimento que tinhamos obtido e agradeceu pelos documentos e conhecimentos passados a ele.

### L4

___

## Soft skills: Crio e mantenho um relacionamento com o cliente, sendo visto e colocando a CI&T como referência

### L3

### L4

___

## Soft skills: Viabilizo e estimulo o time a participar de iniciativas corporativas, mobilizando dentro da área de atuação condizente com meu nível

### L3

### L4