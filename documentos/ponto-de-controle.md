# Lista de Verificação de Design

**Lista de verificação do design do projeto de acordo com o artigo Designing a Complex Software System**

Este documento tem como objetivo comparar as técnicas de design utilizadas no nosso projeto Snake Battle com as utilizadas pelo profissional independente Justin Coulston. Isso se concretizará por meio de uma lista de verificação em que será feito um breve resumo de cada tópico, seguido por uma explicação de como e onde esse conceito foi aplicado no nosso projeto. 


## Introdução

Tendo em vista que Design de Software é a parte da engenharia de software que se encarrega de fazer todo o planejamento anterior ao desenvolvimento, vemos que se trata de um processo muito complexo, em que várias decisões serão tomadas, não existindo um jeito "certo" de fazê-lo.

Com base nisso, Justin Coulston publicou um artigo compartilhando algumas das técnicas que utiliza, seguindo os seguintes tópicos:

- O básico do Design de Software
- Limites do Design de Software
- Processo de Design
- Ferramentas de Design


## O básico do Design de Software

Primeiramente, é importante destacar que é no Design de Software que é feita a definição da visão, dos limites, e dos contratos do sistema, de acordo com as necessidades do negócio, com o objetivo de trazer algum tipo de benefício ao cliente, seja ele financeiro, social ou simplesmente um aumento de eficiência em relação a um outro sistema.

A visão tem como objetivo mostrar as razões e inteções por trás do projeto e quais benefícios ele trará ao ser implementado.

Os limites se referem as restrições a serem seguidas, assim como o suporte necessário para que o objetivo inicial do projeto seja cumprido.

Já o contrato, está relacionado as restrições ou convenções impostas aos componentes, módulos ou aspectos do sistema, geralmente em relação à comunicação, e é essencial para garantir que a interação entre o usuário e a aplicação ocorrerá conforme o esperado.

**Onde isso foi utilizado no nosso projeto?**

Toda essa parte que define o projeto, incluindo o seu escopo, objetivos e restrições está establecida nos arquivos readme e no documento de requisitos. No readme, é mostrada uma visão geral do projeto, explicando como ele vai funcionar e a equipe responsável pelo projeto. Já no documento de requisitos é especificado de forma detalhada essas funções a serem implementadas, feito por meio de histórias de usuário, que é um modelo de escrita que explica as funcionalidades da perspectiva do próprio usuário, além das restrições tecnólogicas, questões de acessibilidade e ambiente de execução da aplicação.

## Limites do Design de Software

Essa seção fala da importância de se manter o design em alto nível e do controle de versão, tendo em vista que a maioria dos projetos são extremamente mutáveis, ainda mais quando se chega na parte do código.

**Onde isso foi utilizado no nosso projeto?**

Para o controle de versão está sendo utilizado git/github. Já na questão do design do sistema, que está sendo realizada por meio de diagramas, a estruturação começa no nível mais genérico, com o diagrama de contexto, e vai se especializando a cada etapa, passando pelos diagramas de container, componentes e classe, tudo isso mantendo apenas a parte das funcionalidades e abstraindo toda a questão relacionada ao código.

## Processo de Design

Essa parte do artigo fala das maneiras de se fazer o design, dando destaque aos métodos top-down e bottom-up.
Enquanto o top-down começa com uma visão geral do sistema e vai se especificando e refinando a cada etapa, definindo os processo com mais detalhes, o bottom-up parte da ideia de juntar diversas funcionalidades básicas, formando um sistema mais complexo no fim.

**Onde isso foi utilizado no nosso projeto?**

No nosso projeto foi utilizada uma apromixamação mais parecida com o top-down, tendo em vista que estruturamos o projeto começando de uma visão mais geral e contextual, com o diagrama de contexto, e com base nesse fomos especificando e detalhando os processos das etapas seguintes, por meio da utilização de outros diagramas e documentos que ofereciam uma visão mais refinada do nosso projeto.

## Ferramentas de Design

Seção que mostra algumas recomendações de ferramentas utilizadas na etapa de design. 

**Onde isso foi utilizado no nosso projeto?**

Para o nosso projeto foi utilizado o lucid chart e o draw.io para a criação dos diagramas.

## Checklist de verificação

- [x] Visão do sistema
- [x] Limites do sistema
- [x] Team contract
- [x] Levantamento de requisitos
- [x] Abordagem de design de software
- [x] Controle de versão
- [x] Design top-down
- [ ] Design bottom-up
- [x] Abstração em nível de código
- [x] Ferramenta de Modelagem
- [ ] Ferramenta de prototipação
