Atividade 01 - Fundamentos e Características da Qualidade no LocalEats
Tarefa 1 - Fundamentos da Qualidade
Necessidades explícitas e implícitas

Tipo: Explícita
Necessidade: Possibilitar que o usuário acesse o sistema por meio de e-mail e senha.
Interessado: Usuário.
Consequência de não ser atendida: O usuário ficará impossibilitado de acessar sua conta e utilizar os recursos associados a ela.

Tipo: Explícita
Necessidade: Permitir que pessoas que ainda não possuem uma conta possam realizar seu cadastro.
Interessado: Novo usuário.
Consequência de não ser atendida: O usuário não poderá criar uma conta e, consequentemente, não conseguirá utilizar o sistema.

Tipo: Implícita
Necessidade: Apresentar mensagens claras que expliquem o motivo de um erro ocorrido durante a tentativa de login.
Interessado: Usuário.
Consequência de não ser atendida: O usuário poderá não compreender a causa do problema e terá dificuldade para saber como solucioná-lo.

Tipo: Implícita
Necessidade: Garantir a segurança das credenciais e das informações da conta, evitando acessos não autorizados.
Interessado: Usuário e responsável pelo sistema.
Consequência de não ser atendida: As informações podem ser expostas ou comprometidas, além de gerar perda de confiança na aplicação.

Análise

Um sistema que implementa todas as funcionalidades explicitamente solicitadas pode, ainda assim, apresentar baixa qualidade? Justifique utilizando pelo menos uma necessidade implícita identificada.

Sim. Mesmo que o sistema possua todas as funcionalidades solicitadas, ele ainda pode apresentar problemas de qualidade caso não atenda às necessidades implícitas dos usuários. Um exemplo seria o LocalEats permitir o acesso à conta, mas apresentar mensagens pouco claras quando ocorre algum erro no login. Nesse caso, apesar de a funcionalidade existir, o usuário pode não compreender o que aconteceu ou como resolver a situação. Por isso, além das funcionalidades explícitas, é importante considerar também as necessidades implícitas.

Tarefa 2 - Exploração da Aplicação

Integrante: Manoela Neves
Funcionalidade: Busca por restaurantes.

O que foi realizado: Foram realizadas duas pesquisas no sistema: uma utilizando uma especialidade existente, "Italiana", e outra utilizando um termo que não possui correspondência, "culinariaxyz".

O que foi observado: Em ambas as situações, o sistema exibiu a mensagem "Nenhum restaurante encontrado".

Evidência: manoela-busca-italiana.png e manoela-busca-semResultados.png

Tarefa 3 - Requisitos e Características de Qualidade

Integrante: Manoela Neves

Requisitos de Qualidade: Quando o usuário pesquisar por uma especialidade disponível no sistema, o LocalEats deve exibir os restaurantes que correspondem ao critério pesquisado.

Características ou Subcaracterísticas: Adequação funcional.

Justificativa: A funcionalidade de busca deve retornar resultados que estejam de acordo com o termo informado pelo usuário. Durante a exploração da aplicação, foi realizada uma pesquisa pela especialidade "Italiana", que está disponível no sistema, porém a aplicação retornou a mensagem "Nenhum restaurante encontrado".

Como avaliar: Efetuar pesquisas utilizando diferentes especialidades disponíveis no sistema e verificar se os restaurantes relacionados ao critério escolhido são apresentados corretamente.

Uso de inteligência artificial

Ferramenta utilizada:
ChatGPT.

Como foi utilizada:
A ferramenta foi utilizada como suporte para interpretar as orientações da atividade, compreender os conceitos envolvidos e auxiliar na estruturação e organização das respostas.

Como as respostas foram verificadas:
As informações sugeridas pela ferramenta foram analisadas e comparadas com os resultados observados durante a utilização do LocalEats e com os conteúdos apresentados e estudados em aula.