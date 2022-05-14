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
|Maria Pérez| Encontrar pessoas interessadas em adotar filhotes de cachorro.| Faço parte de um ONG, que resgata e cuida de
animais abandonados.|
|Victor Mendes| Achar pessoas interessadas em adotar os animais da minha ONG.| Ajudar pessoas encontrarem seu pet ideal para adotar.|

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Permitir que o usuário cadastre tarefas | ALTA | 
|RF-002| Emitir um relatório de tarefas no mês   | MÉDIA |


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | MÉDIA | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s |  BAIXA | 

Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |


Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)
