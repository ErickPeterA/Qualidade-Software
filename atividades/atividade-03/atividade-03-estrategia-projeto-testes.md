Atividade 3 — Estratégia e Projeto de Testes do LocalEats
Tarefa 1 — Planejamento dos testes
1.1 Objetivo dos testes
Avaliar se a funcionalidade de pesquisa do LocalEats permite ao usuário localizar restaurantes utilizando uma especialidade ou localização como critério de busca. Também será verificado se os resultados exibidos estão de acordo com os dados pesquisados e se o sistema evita apresentar restaurantes que não possuem relação com o termo informado.

1.2 Escopo
Integrante: Erick
Funcionalidade incluída: Pesquisa de restaurantes por especialidade ou localização.

O que será verificado: Será analisado se o sistema retorna restaurantes relacionados à especialidade ou localização informada pelo usuário. Também será observado o comportamento da aplicação quando a pesquisa realizada não possui restaurantes correspondentes.

Funcionalidade não incluída: Realização de pedidos.

Justificativa: A realização de pedidos não está relacionada ao fluxo de pesquisa definido como objetivo desta atividade e, por isso, não será considerada nos testes.

1.3 Abordagem
Nível de teste: Sistema.

Justificativa: A funcionalidade será testada diretamente pela interface do LocalEats, considerando o comportamento completo apresentado ao usuário durante a realização de uma pesquisa.

Tipo de teste: Funcional.

Justificativa: O foco dos testes será verificar se a funcionalidade de pesquisa cumpre corretamente sua finalidade e retorna informações compatíveis com os dados fornecidos.

Perspectiva: Caixa-preta.

Justificativa: A avaliação será realizada com base nas entradas fornecidas pelo usuário e nas respostas apresentadas pelo sistema, sem considerar ou analisar a implementação interna do código.

Técnica de teste: Particionamento de equivalência.

Justificativa: Essa técnica permite separar as possíveis entradas em grupos que possuem comportamentos esperados semelhantes. Assim, é possível escolher valores representativos de cada grupo sem precisar testar todas as especialidades, localizações e termos existentes.

1.4 Ambiente e responsabilidades
Ambiente necessário: Aplicação LocalEats disponível para utilização, navegador atualizado, computador ou notebook conectado à internet e existência de restaurantes cadastrados contendo informações de especialidade e localização.

Responsável pelo planejamento: Matheus.

Responsável pela especificação dos casos de teste: Erick.

Responsável pela futura execução dos testes: Matheus.

1.5 Critérios
Critério de entrada: O LocalEats deve estar funcionando e possuir restaurantes cadastrados com informações de especialidade e localização suficientes para a realização dos testes definidos.

Critério de saída: Todos os casos de teste planejados deverão ser executados posteriormente, com seus respectivos resultados registrados, permitindo comparar o comportamento encontrado com o resultado esperado.

Critério de suspensão: A execução deverá ser interrompida caso o sistema esteja indisponível ou não existam informações cadastradas suficientes para realizar as pesquisas previstas.

Tarefa 2 — Riscos e técnicas de teste
2.1 Análise dos riscos
ID	Integrante	Funcionalidade	Risco	Consequência	Probabilidade	Impacto	Prioridade	Justificativa
R01	Erick	Pesquisa de restaurantes por especialidade ou localização	A busca retornar restaurantes que não possuem relação com o termo pesquisado	O usuário poderá receber informações incorretas e encontrar dificuldades para localizar um restaurante que realmente atenda ao que procura	Média	Média	Média	A pesquisa é importante para a navegação pelos restaurantes e resultados incorretos podem afetar negativamente a utilização do sistema
R02	Matheus	Pesquisa de restaurantes por especialidade ou localização	A busca deixar de apresentar um restaurante que possui cadastro correspondente ao termo informado	O usuário pode entender que não existem restaurantes daquela especialidade ou localização e acabar não encontrando uma opção que está disponível no sistema	Média	Alta	Alta	O problema impede que restaurantes existentes sejam localizados e afeta diretamente a principal finalidade da funcionalidade de pesquisa

2.2 Aplicação da técnica
Integrante responsável: Erick.

Funcionalidade: Pesquisa de restaurantes por especialidade ou localização.

Riscos relacionados: R01 e R02.

Técnica escolhida: Particionamento de equivalência.

Por que a técnica foi escolhida?
O particionamento de equivalência foi selecionado porque existem diferentes tipos de informações que podem ser utilizadas na pesquisa, não sendo necessário testar todas as possibilidades existentes.

Dessa maneira, os dados podem ser separados em grupos com comportamentos semelhantes, permitindo escolher exemplos representativos de cada grupo para verificar se o sistema funciona conforme o esperado.

Aplicação da técnica
Foram definidas as seguintes classes de equivalência:

Classe	Situação	Valor representativo
CE01 — Com correspondência	Especialidade que possui pelo menos um restaurante cadastrado	Uma especialidade existente no LocalEats
CE02 — Com correspondência	Localização relacionada a pelo menos um restaurante cadastrado	Uma localização existente no LocalEats
CE03 — Sem correspondência	Termo que não possui relação com nenhum restaurante cadastrado	Um termo que não existe na aplicação

Casos derivados
CE01: CT01 — Realizar uma pesquisa utilizando uma especialidade cadastrada.

CE02: CT02 — Realizar uma pesquisa utilizando uma localização cadastrada.

CE03: CT03 — Realizar uma pesquisa com um termo que não possui correspondência.

Tarefa 3 — Casos de teste e rastreabilidade
3.1 Especificação dos casos de teste
CT01 — Pesquisa utilizando uma especialidade existente
Integrante responsável: Matheus.

Funcionalidade: Pesquisa de restaurantes por especialidade ou localização.

Risco relacionado: R01 e R02.

Técnica utilizada: Particionamento de equivalência — CE01.

Pré-condição: O LocalEats deve estar disponível e deve haver pelo menos um restaurante cadastrado com a especialidade selecionada para o teste.

Dados de entrada: Uma especialidade existente entre os restaurantes cadastrados no sistema.

Passos:

Acessar a página inicial do LocalEats.

Identificar o campo destinado à pesquisa.

Digitar uma especialidade que exista no sistema.

Executar a pesquisa.

Conferir os restaurantes retornados.

Resultado esperado: O sistema deve mostrar um ou mais restaurantes relacionados à especialidade pesquisada, sem apresentar restaurantes que não tenham relação com o termo utilizado.

CT02 — Pesquisa utilizando uma localização existente
Integrante responsável: Erick.

Funcionalidade: Pesquisa de restaurantes por especialidade ou localização.

Risco relacionado: R01 e R02.

Técnica utilizada: Particionamento de equivalência — CE02.

Pré-condição: O LocalEats deve estar disponível e deve existir pelo menos um restaurante cadastrado na localização utilizada no teste.

Dados de entrada: Uma localização existente associada aos restaurantes cadastrados.

Passos:

Entrar na página inicial do LocalEats.

Encontrar o campo de pesquisa.

Informar uma localização existente.

Executar a busca.

Analisar os resultados apresentados.

Resultado esperado: O sistema deve retornar restaurante(s) relacionado(s) à localização informada e não deve incluir resultados que não correspondam ao termo pesquisado.

CT03 — Pesquisa com termo sem correspondência
Integrante responsável: Matheus.

Funcionalidade: Pesquisa de restaurantes por especialidade ou localização.

Risco relacionado: R01.

Técnica utilizada: Particionamento de equivalência — CE03.

Pré-condição: A aplicação LocalEats deve estar disponível para utilização.

Dados de entrada: Um termo que não esteja associado à especialidade ou localização de nenhum restaurante cadastrado.

Passos:

Acessar a página inicial do LocalEats.

Localizar o campo de pesquisa.

Digitar um termo que não possua correspondência com os restaurantes cadastrados.

Realizar a pesquisa.

Observar a resposta apresentada pelo sistema.

Resultado esperado: O sistema não deve retornar restaurantes que não tenham relação com o termo informado na pesquisa.

3.2 Matriz de rastreabilidade
Integrante	Funcionalidade	Risco ou requisito	Técnica utilizada	Casos de teste
Erick	Pesquisa de restaurantes por especialidade ou localização	R01 — Retornar restaurantes que não correspondem ao termo pesquisado	Particionamento de equivalência	CT01, CT02 e CT03
Matheus	Pesquisa de restaurantes por especialidade ou localização	R02 — Deixar de apresentar um restaurante correspondente ao termo pesquisado	Particionamento de equivalência	CT01 e CT02

Uso de inteligência artificial
Ferramenta utilizada: ChatGPT.

Como foi utilizada: A ferramenta serviu como apoio para organizar o documento, estruturar as informações e melhorar a clareza na descrição dos casos e estratégias de teste.

Uma sugestão que precisou ser alterada ou rejeitada: Durante a elaboração, foi considerada a possibilidade de incluir um teste utilizando o campo de pesquisa vazio. Porém, esse cenário foi retirado para manter o foco nos três casos de teste definidos para a funcionalidade selecionada.

Como as respostas foram verificadas: As informações foram conferidas considerando as orientações apresentadas na atividade, as características da funcionalidade do LocalEats e a relação estabelecida entre os riscos identificados, a técnica de teste selecionada e os casos de teste elaborados.