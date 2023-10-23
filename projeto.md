<img src='/img/logo_oficial.jpeg' alt='logo da empresa' width='100px' heidth='100px'/>

# *CREATIVE MIND*

# PROJETO DE SOFTWARE

## *Stakeholders*
|NOME|CARGO|E-MAIL|
|:---|:---|:---|
|Leonardo Pereira Mendes Ribas|Gerente de Projeto|loen.ribas20@gmail.com|
|Patricia de Oliveira Silva|Engenheira de Software|patriciaoliveirasilva155@gmail.com|
|Keila Rodrigues Silva|Analista de Sistemas|rodrigueskeila570@gmail.com|
|Caliane Antoniely Magalhães|Programadora Front-end|calianeantonielly@gmail.com|
|Gabrielly Serafim de Oliveira|Programadora Back-end|gabriellyoliveira.ifro@gmail.com|

# Sumário

* [RESUMO DO PROJETO](#resumo-do-projeto)
* [INTRODUÇÃO](#introdução)
  * [PROPÓSITO DESTE DOCUMENTO](#propósito-deste-documento)
  * [ESCOPO DO PROJETO](#escopo-do-projeto)
  * [CONCEPÇÃO DO SISTEMA](#concepção-do-sistema)
  * [CONVENÇÕES, TERMOS E ABRIVEAÇÕES](#convenções-termos-e-abreviações)
* [DESCRIÇÃO GERAL](#descrição-geral)
  * [USUÁRIOS DO SISTEMA](#usuários-do-sistema)
  * [ABRANGÊNCIA E SISTEMAS SIMILARES](#abrangência-e-sistemas-similares)
  * [SUPOSIÇÕES E DEPENDÊNCIAS](#suposições-e-dependências)
* [ESTUDO DE VIABILIDADE](#estudo-de-viabilidade)
  * [VIABILIDADE TÉCNICA](#viabilidade-técnica)
  * [VIABILIDADE ECONÔMICA](#viabilidade-econômica)
  * [VIABILIDADE ORGANIZACIONAL](#viabilidade-organizacional)
* [METODOLOGIA ADOTADA NO DESENVOLVIMENTO](#metodologia-adotada-no-desenvolvimento)
* [REQUISITOS DO SOFTWARE](#requisitos-do-software)
  * [REQUISITOS FUNCIONAIS](#requisitos-funcionais)
  * [REQUISITOS NÃO FUNCIONAIS](#requisitos-não-funcionais)
* [PROTOTIPAGEM](#prototipagem)
* [DIAGRAMA DE CASOS DE USO](#diagrama-de-casos-de-uso)
  * [ESPECIFICAÇÃO DOS CASOS DE USO](#descrição--especificação-dos-casos-de-uso)
* [DIAGRAMA DE CLASSES](#diagrama-de-classes)
* [DIAGRAMA DE SEQUÊNCIAS](#diagrama-de-sequências)
* [ DIAGRAMA DE ATIVIDADES](#diagrama-de-atividades)
* [REFERÊNCIAS](#referências)


# RESUMO DO PROJETO
| ITEM | DESCRIÇÃO|
|:---|:---|
| NOME DO PROJETO | Creative Mind |
| GERENTE DO PROJETO | Leonardo Pereira Mendes Ribas |
| PRINCIPAL OBJETIVO | Auxiliar as pessoas a criarem novos contos e histórias no site, além de realizar postagens em fórum sobre seus gostos. |
| BENEFÍCIOS ESPERADOS |* Desenvolvimento da criatividade;<br/>* Desenvolvimento do pensamento crítico;<br/>* Desenvolvimento da imaginação;<br/>* Fortalecer a comunicação dentro de uma comunidade;<br/>* Criar hábito de leitura|
| INÍCIO E TÉRMINO PREVISTOS | 14/03/2023 - 07/12/2023 |

[ [INÍCIO](#creative-mind) ]

# INTRODUÇÃO

## PROPÓSITO DESTE DOCUMENTO

Este documento destina-se aos clientes, engenheiros, gerentes e demais stakeholders deste projeto. O propósito deste documento é apresentar a descrição dos serviços e funções que o sistema **_Creative Mind_** deve prover, bem como as suas restrições de operação e propriedades gerais, a fim de ilustrar uma descrição detalhada do sistema para um auxílio durante as etapas de análise, projeto e testes. O documento especifica todos os requisitos funcionais e não funcionais do sistema e contém a prototipagem, além de diagramas UML que foram construídos levando-se em conta as funcionalidades identificadas durante a fase de concepção do sistema.

## CONCEPÇÃO DO SISTEMA

Foram usados três métodos para que pudessem ser obtidos os requisitos do sistema:
* Entrevista:
  * Discussões individuais de um representante da equipe com Fernanda, gerente de conteúdo do fórum de leitura, para entender as necessidades dos usuários e as expectativas da empresa;
* Consulta com especialista:
  * Miguel, professor de literatura da Universidade Federal, orientou a equipe na concepção do sistema, devido à sua vasta experiência no ensino e leitura de literatura;
  * Larissa, professora de biblioteconomia da Universidade Estadual, orientou na análise de requisitos, devido à sua grande experiência em bibliotecas digitais e fóruns de discussão;
* Prototipação:
  * Representações das interfaces gráficas com diferentes níveis de fidelidade, aprovadas pela empresa contratante, para garantir que as necessidades dos usuários fossem atendidas e a experiência do usuário fosse aprimorada.



## CONVENÇÕES, TERMOS E ABREVIAÇÕES

Para evitar interpretações incorretas deste documento, algumas convenções e termos específicos são descritos a seguir:

* TBR: significa "To Be Read", ou seja, "a ser lido". É comumente usado para se referir a uma lista de livros que alguém planeja ler.
* DNF: significa "Did Not Finish", ou seja, "não terminei". É usado para indicar que alguém começou a ler um livro, mas não conseguiu terminar.
* OTP: significa "One True Pairing", ou seja, "o único par verdadeiro". É usado para se referir a um casal em um livro que os fãs acreditam que deveriam estar juntos.
* POV: significa "Point of View", ou seja, "ponto de vista". É usado para se referir ao narrador ou ao personagem principal de uma história.
* ARC: significa "Advance Reader Copy", ou seja, "cópia para leitores antecipados". É usado para se referir a cópias de livros que são enviadas antecipadamente a revisores ou influenciadores para análise antes do lançamento oficial.
* HEA: significa "Happily Ever After", ou seja, "felizes para sempre". É usado para se referir ao final feliz de um livro ou de um relacionamento romântico.
* MC: significa "Main Character", ou seja, "personagem principal". É usado para se referir ao personagem principal de uma história.
* NA: significa "New Adult", ou seja, "jovem adulto". É usado para se referir a livros que apresentam personagens em seus vinte e poucos anos.
* YA: significa "Young Adult", ou seja, "jovem adulto". É usado para se referir a livros que apresentam personagens adolescentes.

[ [INÍCIO](#creative-mind) ]

# DESCRIÇÃO GERAL

## ESCOPO DO PROJETO

### NO ESCOPO

O projeto consiste na construção de uma plataforma de fórum de leitura para gerenciamento de aprendizado, que possa atender os requisitos de uma livraria virtual, no fator de promoção da leitura e engajamento da comunidade de leitores. O projeto visa auxiliar a livraria através de ferramentas de discussão síncronas e assíncronas que serão usadas por funcionários, autores e leitores da comunidade literária. A plataforma terá recursos de avaliação de livros, recomendação de leituras e integração com as principais redes sociais para fomentar discussões e promover a participação ativa dos membros da comunidade.
O escopo do **produto** pode ser consultado nos [requisitos do software](#requisitos-do-software)

### FORA DO ESCOPO

Não fazem parte do escopo do projeto:
* Venda de livros físicos;
* Integração com outras livrarias virtuais;
* Suporte de aprendizagem de idiomas.

## Usuários do sistema
|USUÁRIO|DESCRIÇÃO|
|:---|:---|
|**Usuário**|É um visitante do site que criou uma conta para participar do fórum de leitura. Pode postar comentários, iniciar tópicos de discussão e participar de grupos de discussão.|
|**Administrador**|Responsável pela gestão geral do site, incluindo a moderação de conteúdo, o gerenciamento de usuários, a manutenção do servidor e outras atividades de administração. Pode editar, excluir e mover postagens e tópicos, conceder permissões especiais para usuários, gerenciar recursos do servidor e realizar outras tarefas administrativas.|
|**Moderador**|É um usuário com permissões especiais para moderar o conteúdo do fórum de leitura. Pode editar, excluir e mover postagens e tópicos, monitorar o comportamento dos usuários e aplicar medidas disciplinares quando necessário.|
|**Membro VIP**|É um usuário que ganhou privilégios especiais por ser um membro ativo e contribuir com conteúdo de qualidade para o fórum de leitura. Pode acessar áreas restritas do site, ter sua postagem destacada na página inicial, entre outros benefícios.|
|**Visitante**|É um usuário que acessa o site sem criar uma conta. Pode visualizar o conteúdo público, mas não pode postar comentários ou iniciar novos tópicos de discussão.|

## Abrangência e sistemas similares

### Abrangência:

O objetivo principal do sistema é criar uma plataforma para que os usuários possam interagir e discutir sobre temas relacionados à leitura, além de promover a divulgação de livros e autores. O sistema deve ser intuitivo, fácil de usar e ter uma interface agradável, para incentivar a participação dos usuários e tornar a experiência do usuário agradável. Outros requisitos importantes podem incluir segurança dos dados dos usuários, gerenciamento de conteúdo, relatórios e análises de desempenho, entre outros.

O sistema pode oferecer várias funcionalidades para facilitar a interação e o compartilhamento de informações entre os usuários.

Algumas das funcionalidades que o sistema pode oferecer são:

* **Criação de tópicos:** permitir que os usuários criem novos tópicos de discussão sobre livros, autores, gêneros literários, entre outros assuntos relacionados à leitura;

* **Postagem de comentários:** permitir que os usuários postem comentários em tópicos de discussão e conversem entre si sobre os diferentes aspectos da leitura;

* **Criação de grupos de discussão:** permitir que os usuários criem grupos de discussão privados sobre tópicos específicos, como clubes de leitura, grupos de discussão sobre literatura infantil, entre outros;

* **Mensagens privadas:** permitir que os usuários enviem mensagens privadas uns aos outros para discutir assuntos específicos ou trocar informações pessoais.

### Sistemas similares:

No cenário atual, existem diversos sistemas que são utilizados pelos usuários, porém esses sistemas não atendem todas as necessidades, não sendo considerado satisfatório pela maioria dos usuários.

No cenário nacional encontram-se dois sistemas que se destacam:

**Skoob:** O Skoob é um site brasileiro de leitura que funciona como uma rede social para leitores. Os usuários podem criar perfis e adicionar livros que já leram, que estão lendo ou que pretendem ler. Além disso, o site possui uma seção de fórum onde os usuários podem discutir sobre livros, autores e outras temáticas literárias. Também é possível avaliar os livros, criar listas de leitura e participar de desafios literários.

**Leitura Virtual:** O Leitura Virtual é um site brasileiro de leitura que oferece um amplo catálogo de livros para download gratuito em formato PDF. Além disso, o site possui uma seção de fórum onde os usuários podem discutir sobre livros e outras temáticas literárias. O site também conta com uma seção de resenhas e críticas literárias escritas pelos próprios usuários.

E no cenário internacional possuem os seguintes sistemas bem conhecidos:

**Goodreads:** O Goodreads é um site internacional de leitura que também funciona como uma rede social para leitores. Com mais de 90 milhões de usuários, o site possui uma ampla variedade de recursos, incluindo uma seção de fórum onde os usuários podem discutir sobre livros, autores e outras temáticas literárias. Além disso, os usuários podem avaliar os livros, criar listas de leitura, participar de desafios literários e receber recomendações de livros com base em seus interesses.

**LibraryThing:** O LibraryThing é um site internacional de leitura que oferece um catálogo online para que os usuários possam catalogar suas coleções de livros. Além disso, o site possui uma seção de fórum onde os usuários podem discutir sobre livros e outras temáticas literárias. Os usuários também podem avaliar os livros, criar listas de leitura e receber recomendações de livros com base em seus interesses. O LibraryThing é conhecido por sua ampla comunidade de bibliófilos e amantes da literatura.

## Suposições e dependências
O sistema necessita de um servidor web para sua hospedagem.

Os usuários que forem acessar o site devem utilizar um computador com a seguinte configuração mínima:

* Processador Dual Core 2GHz ou superior
* 2Gb de memória RAM
* 500Mb de armazenamento em disco
* Para uso do site é preciso ter instalado o Java SE versão 8.

# ESTUDO DE VIABILIDADE

Uma vez definidos a necessidade para o sistema e seus requisitos de negócio, é possível compreender melhor o projeto do sistema proposto para elaborar o estudo de viabilidade com os seguintes destaques:

## Viabilidade Técnica
Os colaboradores da empresa contratante possuem considerável experiência em desenvolvimento web e estão familiarizados com a criação de sites interativos. Os analistas também possuem conhecimentos sólidos em tecnologias modernas e tendências relacionadas a fóruns de leitura online. No entanto, o sistema utiliza uma tecnologia nova e emergente que os analistas e programadores não têm experiência prévia. Quanto ao tamanho do sistema, trata-se de um projeto de médio porte, com um nível moderado de complexidade, pois envolve recursos interativos, design responsivo e integração com outras plataformas, como mídias sociais e sistemas de recomendação de livros. Estima-se que o site atenderá a uma base de usuários significativa, com potencial para milhares de membros ativos. Apesar dos desafios relacionados à tecnologia nova e complexidade moderada, o projeto ainda é viável tecnicamente, considerando-se os benefícios esperados e os riscos identificados como controláveis.

## Viabilidade Econômica

Foi realizada uma análise de custo-benefício abrangente, levando em consideração os investimentos necessários para o desenvolvimento, manutenção e promoção do site de fórum de leitura moderna. Mesmo com estimativas conservadoras em relação ao retorno sobre o investimento e aos benefícios totais, o projeto demonstra viabilidade econômica.

## Viabilidade Organizacional

Do ponto de vista organizacional, este projeto de criação de um site de fórum de leitura moderna apresenta baixo risco. A administração e os responsáveis pela gestão da plataforma têm mostrado um forte interesse no projeto, reconhecendo a importância de promover a interação e o compartilhamento de conhecimento entre os leitores. Dessa forma, considerando o interesse e apoio dos gestores, bem como a demanda latente por uma ferramenta específica para discussões literárias, a viabilidade organizacional do projeto é sólida.


[ [INÍCIO](#creative-mind) ]

# Metodologia Adotada no Desenvolvimento

A aplicação da metodologia Scrum se revela altamente vantajosa para o desenvolvimento desse site. Isso se deve à necessidade de adaptabilidade e eficiência no contexto dinâmico de um ambiente literário, desde o início da construção do software até as futuras evoluções. O Scrum oferece capacidade de se adaptar a mudanças rápidas e incorporar novas funcionalidades à medida que as preferências e necessidades dos leitores evoluem. Portanto, a escolha do Scrum como metodologia de desenvolvimento é uma abordagem estratégica que alinha eficácia, flexibilidade e satisfação do usuário em um site de fórum de leitura moderna.

[ [INÍCIO](#creative-mind) ]

# Requisitos do Software

A especificação dos requisitos deste documento deve seguir as recomendações da norma IEEE Std-830-1998, levando em conta as recomentações do documento de [características dos requisitos](caracteristicas_requisitos.md).

## Requisitos Funcionais

A tabela a seguir contém a relação dos Requisitos Funcionais elicitados, com as colunas: identificador, nome, descrição e prioridade:

| IDENTIFICADOR | NOME | DESCRIÇÃO |
:---|:---|:---|
|RF-001 | Criar conta | Permitir que os usuários se inscrevam no site criando uma nova conta de usuário. |
|RF-002 | Solicitar dados | Solicitar as informações necessárias para criar uma conta de usuário, como nome, endereço de e-mail e senha. |
|RF-003 | Verificar e-mail | Verificar se o endereço de e-mail fornecido é válido e não foi usado anteriormente para criar uma conta de usuário. |
|RF-004 | Fazer login | Permitir que os usuários façam login no site usando suas credenciais de conta de usuário. |
|RF-005 | Atualizar dados | Permitir que os usuários atualizem suas informações de conta, como nome, endereço de e-mail e senha. |
|RF-006 | Visualizar dados | Permitir que os usuários visualizem suas informações de conta, como histórico de login e atividades recentes. |
|RF-007 | Excluir conta | Permitir que os usuários excluam sua conta, se desejarem. |
|RF-008 | Recuperar senha | Possibilitar que os usuários recuperem suas senhas, caso as esqueçam. |
|RF-009 | Confirmar conta | Enviar um e-mail de confirmação para os usuários após a criação de uma nova conta. |
|RF-010 | Mostrar notificações | Permitir que os usuários optem por receber atualizações por e-mail do site, como notificações de novas postagens em fóruns de interesse. |
|RF-011 | Configurar notificações | Permitir que os usuários alterem suas preferências de e-mail, escolhendo quais tipos de notificações desejam receber. |
|RF-012 | Bloquear usuário | Permitir que os usuários bloqueiem outros usuários, impedindo-os de enviar mensagens privadas ou interagir em fóruns específicos. |
|RF-013 | Denunciar conteúdo | Possibilitar que os usuários relatem conteúdo inapropriado ou violações de termos de serviço. |
|RF-014 | Modificar informações do usuário | Permitir que os administradores do site modifiquem as informações de conta dos usuários, se necessário. |
|RF-015 | Banir usuário | Permitir que os administradores do site excluam as contas dos usuários, se necessário. |
|RF-016 | Ver usuários | Permitir que os administradores do site vejam uma lista de todas as contas de usuário registradas no site. |
|RF-017 | Modificar configurações | Possibilitar que os administradores do site modifiquem as configurações de privacidade e segurança do site. |
|RF-018 | Gerenciar permissões | Permitir que os administradores do site gerenciem permissões de acesso para grupos de usuários, como moderadores e administradores. |
|RF-019 | Denunciar usuário | Permitir que os usuários denunciem outras contas por atividades suspeitas ou comportamento inadequado. |
|RF-020 | Configurar privacidade | Possibilitar que os usuários definam suas preferências de privacidade, controlando quem pode ver suas informações de perfil e atividades no site. |


## Requisitos Não Funcionais
A tabela a seguir contém a relação com os Requisitos Não Funcionais identificados, contendo identificador, nome, descrição e prioridade:

| IDENTIFICADOR | NOME | DESCRIÇÃO |
|:---|:---|:---|
|RNF-001 |Segurança  | A capacidade do sistema de proteger informações. |
|RNF-002 |Escalabilidade | Lidar com um aumento de demanda sem que isso afete o desempenho. |
|RNF-003 |Disponibilidade| Estar sempre disponível, sem paralizações prolongadas. |
|RNF-004 |Confiabilidade | Capacidade de ser confiável, realizando suas funções de forma consistente sem falhas. |
|RNF-005 |Desempenho | A capacidade do sistema de lidar com grandes volumes de dados de forma rápida e eficiente. |
|RNF-006 |Mantenabilidade | A capacidade do sistema de ser facilmente mantido e atualizado, sem ser interrompido. |
|RNF-007 |Capacidade | Capacidade do sistema de ser monitorado e gerenciado facilmente pelos administradores do sistema. |
|RNF-008 |Adaptabilidade |  A facilidade do sitema de se adaptar a diferentes ambientes. |
|RNF-009 |Usabilidade | Facilidade para que os usiarios possam interagir com o sistema. |
|RNF-0010|Interoperabilidade | O sistema podera se integrar facilmente a outros sistemas ou aplicativos. |




[ [INÍCIO](#creative-mind) ]


# Prototipagem

[Link do Protótipo criado no FIGMA](https://www.figma.com/file/n63YBCVZ7Careh4693idSD/Creative-Mind?type=design&node-id=13%3A2&t=GkJwHtMVwcv2oqdc-1)

![Imagem do Protótipo](/img/creative_mind_no_macbook.png)

[ [INÍCIO](#creative-mind) ]


# Diagrama de Casos de Uso

![Diagrama de Casos de Uso](/img/Creative_Mind_Diagrama.png)

## Descrição / Especificação dos Casos de Uso

### UC-01 - Cadastrar Professor

|UC-01 - Cadastrar Professor|           
|:---|
|**Descrição/Objetivo:** Permite a inclusão de novos professores no Sistema|
|**Atores: Administrador**|
|**Pré-condições:** O usuário precisa estar cadastrado e logado|
|**Pós-condições:** Será apresentada uma mensagem confirmando a realização do cadastro|
|**FLUXO PRINCIPAL / BÁSICO:**|
|1. O usuário seleciona a opção cadastrar professor|
|2. Os dados do professor são inseridos|
|3. O usuário clica em salvar|
|4. Um novo ID é gerado |
|5. É apresentada uma mensagem confirmando a realização do cadastro|
|**FLUXOS ALTERNATIVOS / EXCESSÕES:** |
|**A1: Campo obrigatório não preenchido** |
|1. Uma mensagem será apresentada para o usuário, informando que existe(m) campos obrigatórios que não foram preenchidos |
|2. O cursor será posicionado no primeiro campo obrigatório que não foi preenchido |
|**A2: Data de nascimento inválida** |
|1. Uma mensagem será apresentada para o usuário, informando que a data informáda não é válida|
|2. O cursor será posicionado para o campo data|


## Matriz de Rastreabilidade


<<<<<<< HEAD
| REQUISITO |UC-Cadastrar|UC-inserir dados|UC-03|UC-04|UC-05|UC-06|UC-07|UC-08|UC-09| UC-10|     
||:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|
|RF-001|X| | | | | | | | | |
|RF-002| |X| |X| | | | | | |
=======
| REQUISITO |Criar conta|Solicitar dados|Verificar e-mail|Fazer Login|Visualizar dados|Excluir conta|Mostrar notificações|Configurar notificações|Bloquear usuário|Denunciar conteúdo| 
|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|
|RF-001|X|X| | | | | | | | |
|RF-002|X|X| | | | | | | | |
|RF-003| | |X| | | | | | | |
|RF-004| | | |X| | | | | | |
|RF-005| | | | |X|X|X| | | |
|RF-006| | | | |X|X|X| | | |
|RF-007| | | | | |X|X| | | |
|RF-008| | | | | |X|X| | | |
|RF-009| | |X| | | | | | | |
|RF-010| | | | | | |X| | | |
|RF-011| | | | | | |X|X| | |
|RF-012| | | | | | |X| |X| |
|RF-013| | | | | | |X| | |X|
|RF-014| | | | | | |X| |X| |
|RF-015| | | | | | |X| |X|X|
|RF-016| | | | | | |X| |X| |
|RF-017| | | | | | |X| | | |
|RF-018| | | | | | |X| |X| |
|RF-019| | | | | | |X| |X|X|
|RF-020| | | | | | |X| | | |
>>>>>>> 39352deb6b1d5de2a13e02db7048f9cdc05c0e1a

[ [INÍCIO](#creative-mind) ]

# Diagrama de Classes

![Diagrama de Classes](/img/CreativeMindClasses.png)

[ [INÍCIO](#creative-mind) ]

# Diagrama de Sequências

![Denunciar Conteúdo](/img/Denunciar_Conteúdo.png)
![Bloquear Usuário](/img/BloquearUsuario.png)
![Excluir Conta](/img/excluir_conta.png)
![Mostrar Notificações](/img/Mostrar_notificações.png)
[ [INÍCIO](#creative-mind) ]

# Diagrama de Atividades


# REFERÊNCIAS

Esta subseção apresenta as referências aos documentos que utilizamos no auxílio à construção deste documento.
* [UML](https://www.omg.org/spec/UML/2.5/About-UML/)
* [Práticas para Especificação de Requisitos IEEE-830](https://ieeexplore.ieee.org/document/720574)
