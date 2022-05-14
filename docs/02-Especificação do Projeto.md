# Especificações do Projeto

Levantamos uma pesquisa simulada para definir o alvo do projeto, usando como modelo histórias de algumas pessoas. Usando estas pessoas como base, elaboramos pontos de interesse para serem adicionados ao projeto, onde os membros da equipe consolidaram o objetivo primordial do projeto. Esta pesquisa foi dividida em duas etapas: Personas e Histórias de Usuários.

## Personas

As pessoas entrevistadas durante o processo de resolução de problemas estão representadas nos diagramas a seguir.

________________________________________________________________________________________
Nome | Idade | Ocupação
---|---|---
 **Sandra Regina** | 45 anos | Professora de história em uma escola de médio porte.

Aplicativos | Detalhes Pessoais | Frustrações | Hobbies/História
---|---|---|---
Instagram<br> Facebook<br> Youtube | Mora em Belo horizonte, Casada e Não tem filhos. | Perdeu um dos seus pets. | Sou dedicada, alegre, comunicativa e amo animais de estimação. Passo o meu tempo lendo livros, fazendo caminhada e amo passar meu tempo com meus pets. 

________________________________________________________________________________________
Nome | Idade | Ocupação
---|---|---
 **Willian Silva** | 27 anos | Publicitário, trabalho em uma empresa privada no departamento de marketing e comunicação.

Aplicativos | Detalhes Pessoais | Frustrações | Hobbies/História
---|---|---|---
Instagram<br> Facebook<br> Youtube<br> LinkedIn<br> Zoom | Mora em Belo horizonte, Solteiro e Mora sozinho. | Viaja muito e quase não tem tempo;<br> Está querendo doar seu animal por falta de tempo para cuidar. | Sou alegre, otimista, e apaixonado por fazer aquilo que faz. No meu tempo livre viajar e conhecer lugares novos.

________________________________________________________________________________________
Nome | Idade | Ocupação
---|---|---
 **João Paulo** | 32 anos | Motorista de aplicativo.

Aplicativos | Detalhes Pessoais | Frustrações | Hobbies/História
---|---|---|---
Facebook<br> Youtube<br> Telegram | Mora em Belo Horizonte, Casado e tem 1 filho | Não ter conquistado minha casa própria. | Nasci no interior de Minas Gerais, vim para Belo Horizonte com 15 anos de idade, a procura de melhores
oportunidades de trabalho. Já trabalhando como trocador de ônibus, conheci minha atual esposa, com quem me casei e
atualmente temos um filho de 5 anos.<br> Futebol, games e skate.

________________________________________________________________________________________
Nome | Idade | Ocupação
---|---|---
 **Valentina Pereira** | 23 anos | Influenciadora, tenho 53mil seguidores no Instagram e um canal no YouTube com 17 mil inscritos.

Aplicativos | Detalhes Pessoais | Frustrações | Hobbies/História
---|---|---|---
Instagram<br> Facebook<br> Youtube<br> Zoom | Mora em Belo horizonte, Solteira, Mora sozinho e Não tem filhos. | Não ter alcançado meus objetivos e sonhos através da minha profissão. | Nascida e criada em ambiente familiar, não muito tradicional, com os pais separados. Formei no ensino médio e hoje estou cursando publicidade e propaganda.<br> Amo sempre estar com minha família e amigos.

________________________________________________________________________________________
Nome | Idade | Ocupação
---|---|---
 **Maria Pérez** | 44 anos | Secretária em escola particular da educação infantil.

Aplicativos | Detalhes Pessoais | Frustrações | Hobbies/História
---|---|---|---
Waze<br> Twitter<br> Amazon | Mora em Belo Horizonte, Casada e tem 1 filho| Não ter uma saúde equilibrada a aponto de estar acima do meu peso ideal e passar por alguns problemas de saúde. | Por ter perdido meus pais aos 9 anos, tive grandes
responsabilidades muito precoce. Trabalho na mesma empresa a 23 anos. Engravidei aos 19 anos e hoje tenho uma filha, formada e já casada.<br>Adoro sair com meus amigos, viajar e acampar.
________________________________________________________________________________________
Nome | Idade | Ocupação
---|---|---
 **Victor Mendes** | 40 anos | Veterinário.

Aplicativos | Detalhes Pessoais | Frustrações | Hobbies/História
---|---|---|---
Instagram<br> Facebook<br> Youtube | Mora em Belo horizonte, Casado e Não tem filhos. | Ainda alcançar poucas pessoas com os projetos da minha ONG. | Quando adulto tive a iniciativa de criar uma ONG, com a ajuda de parceiros, para encontrar famílias interessadas a adotar animais de rua.<br> Em meu tempo livre gosto de ir Cinema, teatro e museus.

## Histórias de Usuários

As subsequentes histórias de usuários foram registradas com base em uma concepção diária dos papéis identificados pelo projeto.

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Sandra Regina| Quero adotar um cão de pequeno porte.| Acredito que um cão pode trazer felicidade e alegria, após a perda do meu último pet.|
|Wiliam Silva| Achar uma nova moradia para o meu gato Tom.| Vou me mudar pra outro país e infelizmente não vou poder ficar com ele. Quero encontrar alguém que realmente pegue para cuidar, dar todo amor e carinho que ele merece.|
|João Paulo| Adotar um cachorro de grande porte.| Preciso de um cão de guarda na minha casa.|
|Valentina Pereira| Adotar dois ou três gatos filhotes que estejam precisando de suporte, amor e carinho.| Encontrar um novo lar para os filhotes da minha cachorra que deu à luz a 4 cachorrinhos.|
|Maria Pérez| Encontrar pessoas interessadas em adotar filhotes de cachorro.| Faço parte de um ONG, que resgata e cuida de animais abandonados.|
|Victor Mendes| Achar pessoas interessadas em adotar os animais da minha ONG.| Ajudar pessoas encontrarem seu pet ideal para adotar.|

## Requisitos do Projeto

O escopo funcional do projeto é definido por meio dos requisitos funcionais que descrevem as possibilidades interação dos usuários, bem como os requisitos não funcionais que descrevem os aspectos que o sistema deverá apresentar de maneira geral. Estes requisitos são apresentados a seguir.

### Requisitos Funcionais

A tabela a seguir apresenta os requisitos do projeto, identificando a prioridade em que os mesmos devem ser entregues:

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| O sistema deve permitir ao usuário divulgar seu animal (cachorro e gato) para adoção. | ALTA | 
|RF-002| O sistema deve permitir ao usuário encontrar seu animal para adotar, nas características desejadas. | ALTA |
|RF-003| O sistema deve permitir ao usuário fotos e informação necessárias sobre o pet interessado. | MÉDIA |
|RF-004| O sistema deve oferecer um menu que permita ao usuário divulgar fotos e informação daquele animal para adoção. | MÉDIA |
|RF-005| O site deve permitir salvar anúncios interessado pelo usuário. | BAIXA |
|RF-006| O site deve permitir que usuários possam comentar sobre o anúncio. | BAIXA |
|RF-007| O site deve permitir ao usuário um menu Chat, possibilitando a comunicação privada entre o interessado e o anunciante. | ALTA |
|RF-008| O site deve permitir ao usuário criar uma conta privada, possibilitando divulgar e adotar seu animal de estimação. | ALTA |



### Requisitos não Funcionais

A tabela a seguir apresenta os requisitos não funcionais que o projeto deverá atender:

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-01| O site deve ter disponibilidade de servidor web. | ALTA | 
|RNF-02| O site deverá ter certificado ssl. |  ALTA | 
|RNF-03| O site deve ter acesso de todos os usuários de todas as plataformas. | MÉDIA |
|RNF-04| O site deverá ser um site leve e rápido. | MÉDIA |
|RNF-05| O servidor onde o site estará hospedado deve oferecer algum nível de segurança. | ALTA |
|RNF-06| O site deverá ser usado uma arquitetura que comporte transição para uso em Mobile. | MÉDIA |
|RNF-07| O site deverá permitir acessos simultâneos. | MÉDIA |


## Restrições

A tabela abaixo lista as questões que limitam a execução deste projeto e aquelas que criam uma obrigação clara para o desenvolvimento do projeto relacionado.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|RE-01| Esse projeto não deve sofrer atrasos. Tem prazo de entrega (junho, 2022), de acordo com o final do semestre letivo. |
|RE-02| Os integrantes da equipe só podem trabalhar, no projeto, em determinados horários nos dias uteis (de 20:00h as 00:00h) |



