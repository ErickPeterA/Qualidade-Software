Atividade 2 — Organização da Qualidade no LocalEats
Tarefa 1 — Diagnóstico da situação

Problema identificado: Não existem critérios bem definidos para determinar quando uma funcionalidade pode ser considerada concluída.
Possível consequência para o produto ou para a equipe: Uma funcionalidade pode ser entregue sem cumprir todos os requisitos necessários ou sem passar pelas validações adequadas. Isso pode aumentar a quantidade de problemas encontrados pelos usuários e também gerar retrabalho para a equipe.

Problema identificado: Parte da equipe entende que a realização dos testes é uma responsabilidade exclusiva do QA.
Possível consequência para o produto ou para a equipe: A qualidade acaba ficando concentrada em apenas uma função. Dessa forma, problemas que poderiam ser encontrados ainda durante o desenvolvimento podem ser descobertos somente nas etapas finais, tornando sua correção mais trabalhosa e demorada.

Problema identificado: Os defeitos encontrados nem sempre são documentados e acompanhados até sua resolução.
Possível consequência para o produto ou para a equipe: Alguns problemas podem acabar sendo esquecidos, permanecerem sem solução ou voltarem a ocorrer. Além disso, a equipe deixa de ter um histórico organizado sobre os defeitos e seus respectivos status.

A qualidade do LocalEats deve ser responsabilidade exclusiva do profissional de QA?

Não. A qualidade deve ser construída em conjunto por todos os integrantes da equipe. O QA possui um papel especializado na execução e planejamento dos testes, porém o responsável pelo produto, os desenvolvedores e a liderança técnica também possuem participação importante na prevenção de erros e na garantia de que as funcionalidades estejam de acordo com os requisitos definidos.

Tarefa 2 — Papéis e competências
Responsável pelo Produto

Integrante: Erick

Responsabilidades relacionadas à qualidade: Definir os requisitos das funcionalidades, esclarecer dúvidas sobre o comportamento esperado, estabelecer critérios de aceitação, organizar as prioridades e verificar se as entregas correspondem às necessidades dos usuários e do produto.

Competências técnicas: Análise e levantamento de requisitos, criação de critérios de aceitação, organização e priorização do backlog e conhecimento sobre as funcionalidades do sistema.

Competências comportamentais: Boa comunicação, organização, capacidade de decisão, negociação, empatia e foco nas necessidades dos usuários.

Desenvolvedor

Integrante: Matheus

Responsabilidades relacionadas à qualidade: Desenvolver as funcionalidades, executar testes unitários, solucionar problemas encontrados, participar das revisões de código e seguir as práticas e padrões técnicos estabelecidos pela equipe.

Competências técnicas: Conhecimentos de programação, Git, testes unitários, depuração de código e boas práticas de desenvolvimento de software.

Competências comportamentais: Trabalho em equipe, responsabilidade, atenção aos detalhes, comunicação e capacidade de solucionar problemas.

QA / Analista de Qualidade

Integrante: Erick

Responsabilidades relacionadas à qualidade: Planejar e executar testes, criar cenários e casos de teste, validar os critérios de aceitação, registrar e acompanhar defeitos e informar à equipe sobre possíveis riscos relacionados à qualidade.

Competências técnicas: Conhecimento em técnicas de teste, testes funcionais e exploratórios, elaboração de casos de teste, análise de requisitos e controle de defeitos.

Competências comportamentais: Pensamento crítico, atenção aos detalhes, organização, comunicação e capacidade de trabalhar em equipe.

Liderança Técnica

Integrante: Matheus

Responsabilidades relacionadas à qualidade: Apoiar e orientar as decisões técnicas, manter os padrões de desenvolvimento, participar das revisões de código, analisar possíveis riscos técnicos e acompanhar a qualidade das entregas.

Competências técnicas: Desenvolvimento de software, arquitetura de sistemas, revisão de código, Git, integração entre sistemas e boas práticas de desenvolvimento.

Competências comportamentais: Liderança, comunicação, capacidade de análise, tomada de decisão, colaboração e resolução de problemas.

Justificativa dos papéis escolhidos

Os quatro papéis foram selecionados porque cada um possui uma função específica e, ao mesmo tempo, complementar na construção da qualidade do LocalEats.

O Responsável pelo Produto é responsável principalmente por definir o que deve ser entregue, esclarecer o comportamento esperado das funcionalidades e estabelecer as prioridades do sistema.

O Desenvolvedor transforma os requisitos em funcionalidades, contribuindo para a prevenção de problemas por meio de boas práticas de programação, testes unitários e revisão do código.

O QA / Analista de Qualidade possui uma atuação mais direcionada à validação do sistema, planejando e executando testes, encontrando possíveis problemas e acompanhando os defeitos identificados.

Já a Liderança Técnica contribui para a qualidade da parte técnica do projeto, auxiliando nas decisões de implementação, nos padrões de desenvolvimento, nas revisões e na identificação de riscos.

Tarefa 3 — Matriz de responsabilidades
Legenda

R — Responsável: realiza diretamente a atividade.
A — Aprovador: possui a responsabilidade pelo resultado final ou pela decisão.
C — Consultado: participa fornecendo informações ou opiniões antes da execução ou decisão.
I — Informado: deve receber informações sobre o resultado.

Atividade de qualidade	Responsável pelo Produto	Desenvolvedor	QA / Analista de Qualidade	Liderança Técnica
Definir critérios de aceitação	R/A	C	C	I
Revisar requisitos	A	C	R	C
Implementar a funcionalidade	I	R	I	A
Revisar o código	I	R	I	A
Criar testes unitários	I	R/A	C	C
Planejar e executar testes do sistema	C	C	R/A	I
Registrar e acompanhar defeitos	I	C	R/A	I
Priorizar a correção dos defeitos	R/A	C	C	C
Aprovar a disponibilização da versão	A	I	C	R
Lacuna ou conflito encontrado

Lacuna ou conflito: Não existe uma definição totalmente clara sobre quem deve autorizar a disponibilização de uma nova versão do LocalEats.

Possível consequência: Diferentes integrantes podem entender que essa decisão pertence a outro papel. Com isso, existe o risco de uma versão ser liberada sem que haja uma aprovação formal e bem definida.

Solução proposta: A liderança técnica pode ficar responsável por avaliar se a versão apresenta condições técnicas adequadas para ser disponibilizada. Já o responsável pelo produto fica encarregado da aprovação final. O QA participa como consultado, fornecendo os resultados dos testes, os defeitos encontrados e os possíveis riscos identificados.

Práticas recomendadas
Prática 1 — Critérios de aceitação e Definition of Done

Prática recomendada: Estabelecer critérios de aceitação e uma Definition of Done para cada funcionalidade.

Problema que ajuda a resolver: A falta de uma definição clara sobre quais condições precisam ser cumpridas para que uma funcionalidade seja considerada finalizada.

Papéis envolvidos: Responsável pelo Produto, Desenvolvedor, QA e Liderança Técnica.

Como seria aplicada: Antes do desenvolvimento e da conclusão de uma funcionalidade, a equipe deve definir quais requisitos precisam ser atendidos para que ela possa ser considerada pronta.

Na funcionalidade de busca do LocalEats, por exemplo, os critérios de aceitação poderiam incluir:

permitir buscas por tipo de culinária;

possibilitar buscas por localização;

exibir restaurantes relacionados ao termo pesquisado;

apresentar uma mensagem quando não houver resultados;

garantir que os filtros continuem funcionando corretamente.

Além disso, a Definition of Done poderia determinar que uma funcionalidade somente será considerada concluída quando:

o desenvolvimento tiver sido finalizado;

todos os critérios de aceitação forem atendidos;

os testes necessários tiverem sido realizados;

o código tiver passado por revisão;

os defeitos críticos tiverem sido solucionados.

Prática 2 — Registro e acompanhamento de defeitos

Prática recomendada: Adotar um processo padronizado para registrar, acompanhar e resolver os defeitos encontrados.

Problema que ajuda a resolver: Problemas identificados durante os testes que acabam não sendo registrados ou acompanhados corretamente.

Papéis envolvidos: QA, Desenvolvedor, Responsável pelo Produto e Liderança Técnica.

Como seria aplicada: Sempre que um problema for encontrado, ele deve ser documentado com informações que permitam à equipe entender o erro, reproduzi-lo, corrigi-lo e realizar um novo teste posteriormente.

O registro de um defeito pode apresentar informações como:

título do problema;

funcionalidade afetada;

descrição do erro;

etapas necessárias para reproduzi-lo;

comportamento esperado;

comportamento observado;

nível de severidade;

prioridade;

evidências;

situação atual;

responsável pela correção.

Se for identificado um problema na busca, nos filtros, nos favoritos ou em qualquer outra funcionalidade do LocalEats, o defeito deve continuar sendo acompanhado até que seja corrigido e validado novamente.

Exemplo de responsabilidade compartilhada no LocalEats

A funcionalidade de busca do LocalEats demonstra como diferentes integrantes podem participar do processo de qualidade.

Responsável pelo Produto: Determina como a busca deve se comportar e define os critérios que precisam ser atendidos.

Desenvolvedor: Desenvolve a funcionalidade e realiza as verificações técnicas necessárias durante sua implementação.

QA / Analista de Qualidade: Realiza testes utilizando diferentes situações para verificar se a funcionalidade está de acordo com os requisitos estabelecidos.

Alguns exemplos de cenários de teste são:

realizar uma busca por uma culinária existente;

pesquisar por uma localização cadastrada;

realizar uma pesquisa que não apresente resultados;

deixar o campo de pesquisa vazio;

combinar a busca com os filtros disponíveis.

Liderança Técnica: Analisa a solução utilizada, participa da revisão do código e verifica se a implementação segue os padrões técnicos adotados pela equipe.

Assim, a qualidade passa a ser uma responsabilidade coletiva, em que cada integrante contribui de acordo com seu papel, evitando que todo o processo fique concentrado apenas no QA.

Uso de inteligência artificial

Ferramenta utilizada: ChatGPT.

Como foi utilizada: A ferramenta foi utilizada como auxílio para organizar as informações da atividade, melhorar a estrutura do documento e revisar a redação das respostas.

Como as respostas foram verificadas: O conteúdo produzido foi conferido considerando as instruções da atividade, o funcionamento do LocalEats e as definições estabelecidas para os papéis e responsabilidades da equipe.
