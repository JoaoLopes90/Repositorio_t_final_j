# Relatório Final - Página Colaborativa de Receitas

## Integrantes do Grupo
- Nome do projeto:Repositorio_t_final_j
- Integrantes: João Lopes; Marco Saraiva
- Repositório: [https://github.com/JoaoLopes90/Repositorio_t_final_j]

## Branches Criadas
- Descreva as branches criadas e o objetivo de cada uma.
- Informe como os merges foram realizados (com PR? Revisão?).

Bolo-de-Cenoura-com-Cobertura-de-Chocolate
    Objetivo: criar um ramo específico para a receita 1.

Bolo-de-Chocolate-Fofo
    Objetivo: criar um ramo específico para a receita 2.

Bolo-de-Laranja-com-Calda
    Objetivo: criar um ramo específico para a receita 3.

Bolo-Red-Velvet-Com-Creme-De-Queijo
    Objetivo: criar um ramo específico para a receita 4.

Bolo-de-Coco-Humido
    Objetivo: criar um ramo específico para a receita 5

Bolo-de-Milho-com-Doce-de-Goiaba
    Objetivo: criar um ramo específico para a receita 6.
Todos os merges foram realizados através de PRs, onde os integrantes do grupo foram os responsáveis.

## Histórico de Commits
- Exemplo de boas mensagens de commit.
- Print ou link do gráfico de contribuições.
git commit -m "Receita-1" src/index.html
git commit -m "Receita-2" src/index.html
git commit -m "Receita-3" src/index.html
git commit -m "Receita-4" src/index.html
git commit -m "Receita-5" src/index.html
git commit -m "Receita-6" src/index.html

O gráfico está no próprio repositório.

## Issues Criadas
Bolo de Cenoura com Cobertura de Chocolate - responsável: JoaoLopes90
    Mensagem: Criação da receita 1.
Bolo de Chocolate Fofo - responsável: JoaoLopes90
    Mensagem: Criação da receita 2.
Bolo de Laranja com Calda - responsável: JoaoLopes90
    Mensagem: Criação da receita 3.
Bolo Red Velvet Com Creme De Queijo - responsável: saraivasb4
    Mensagem: Criação da receita 4.
Bolo de Coco Humido - responsável: saraivasb4
    Mensagem: Criação da receita 5.
Bolo de Milho com Doce de Goiaba - responsável: saraivasb4
    Mensagem: Criação da receita 6.

## Pull Requests
Descreva o processo de revisão e merges realizados.
Fizemos push de cada ramo para o repositório do GitHub, e depois realizamos o merge dos ramos para o ramo principal já no repositorio do GitHub.

## Conflitos e Resoluções
Explique se houve conflitos e como foram resolvidos.

Tivemos conflitos quando tentámos fazer merge de ramos.
Para resolver os conflitos, analisámos as diferenças entre as versões e:

Removemos os marcadores de conflito (<<<<<<<, =======, >>>>>>>).
Escolhemos o conteúdo correto ou combinámos ambos, conforme o necessário.
Após resolvermos todos os conflitos, guardámos as alterações e concluímos o merge diretamente no GitHub.
Por fim, o GitHub criou automaticamente um novo commit de merge com as resoluções aplicadas.
Este processo permitiu-nos integrar as alterações de diferentes branches de forma colaborativa.

## Dificuldades Enfrentadas
Dúvidas ou problemas que surgiram.

1 - Processo de Commit num Repositório Clonado
Inicialmente, pensávamos que, ao clonar um repositório, seria possível fazer commits diretamente sem passos adicionais. No entanto, percebemos que era necessário utilizar o comando git add para preparar os ficheiros antes de efetuar o commit. Esta etapa é fundamental para que o Git saiba exatamente quais alterações devem ser registadas. Esta experiência ajudou-nos a consolidar o fluxo correto de trabalho com Git: git add seguido de git commit.

2 - Clone sem Conexão ao Repositório no GitHub
Tivemos a dúvida se seria possível clonar o repositório do professor e trabalhar localmente sem configurar imediatamente uma ligação (remoto) ao nosso próprio repositório no GitHub. Testámos essa hipótese e verificámos que funcionava: conseguimos clonar, editar, e fazer commits localmente, mesmo sem ligação ao repositório remoto. Isto mostrou-nos que o Git funciona de forma independente na máquina local, e só é necessária a ligação ao GitHub na altura de fazer push ou sincronizar.

3 - Nomes de Branches com Espaços
Tentámos criar branches com nomes longos contendo espaços (ex: Bolo de Chocolate Fofinho) e percebemos que o Git não aceita espaços em nomes de branches. Foi necessário utilizar caracteres como hífen (-) ou underscore (_) para substituir os espaços. Por exemplo: Bolo-de-Chocolate-Fofinho ou Bolo_de_Chocolate_Fofinho. Esta dificuldade levou-nos a compreender melhor as convenções de nomenclatura no Git.

## Principais Comandos Git Utilizados
Liste e comente comandos importantes usados no projeto.

git branch -> Usámos o esse comando para criar diferentes ramificações, permitindo que cada um trabalhasse em funcionalidades distintas sem interferir no trabalho do outro. Desta forma, conseguimos desenvolver e testar alterações em paralelo, integrando-as mais tarde no ramo principal de forma controlada.

git add * -> Depois de clonarmos o repositório do GitHub, este ficou logo como um repositório local, pronto a ser utilizado. No entanto, após fazermos alterações nos ficheiros, foi necessário usar o comando `git add *` para preparar essas mudanças. Só depois disso conseguimos fazer os commits e registar as alterações no histórico do projeto.

git checkout -> Usámos o comando `git checkout` para mudar entre diferentes ramificações (branches) do projeto. Isto permitiu-nos trabalhar em funcionalidades específicas, corrigir bugs ou testar versões diferentes do código sem interferir no ramo principal. Além disso, também foi útil para voltar a versões anteriores dos ficheiros caso fosse necessário. 

git commit -m "mensagem" -> Usado para registar alterações feitas no projeto, guardando uma versão específica do estado dos ficheiros com uma mensagem descritiva. Isto permitiu manter um histórico organizado, voltar atrás em caso de erro e facilitar o trabalho colaborativo entre os colegas envolvidos.

git branch -v -> Usámos o comando `git branch -v` para verificar as diferentes ramificações do projeto e as suas mensagens de commit. Isso permitiu-nos acompanhar o progresso e as alterações realizadas em cada ramificação, facilitando o trabalho colaborativo e a identificação de conflitos.

git push -> Depois de fazermos os commits com as alterações no repositório local, usámos o comando `git push` para enviar essas mudanças para o repositório remoto no GitHub. Este passo foi essencial para partilhar o nosso progresso entre nós, garantindo que tínhamos sempre a versão mais atualizada do projeto.

Utilizámos a funcionalidade de merge na interface do GitHub para integrar as alterações provenientes de diferentes branches, consolidando assim todo o trabalho desenvolvido numa única versão do projeto.

## Conclusão
A realização deste projeto permitiu-nos consolidar, na prática, os conhecimentos adquiridos sobre o uso do Git e GitHub no desenvolvimento colaborativo de software. Criámos diferentes branches para cada receita, o que facilitou a divisão de tarefas entre os membros do grupo e evitou conflitos de trabalho simultâneo sobre os mesmos ficheiros.

Cometemos e partilhámos as alterações localmente através dos comandos fundamentais do Git, como git branch, git checkout, git add, git commit e git push. Estes comandos foram essenciais para o controlo de versões e para mantermos um fluxo de trabalho sincronizado entre os membros da equipa.

Contudo, é importante referir que o comando de merge foi o único que não realizámos através da linha de comandos. Em vez disso, optámos por usar a interface gráfica do GitHub para criar e gerir os Pull Requests, onde cada branch foi revista e integrada no ramo principal de forma visual e colaborativa. Esta abordagem facilitou a gestão dos merges e a resolução de conflitos diretamente no browser, proporcionando uma melhor experiência para quem ainda está a consolidar os conceitos de Git.

As dificuldades encontradas ao longo do projeto, como dúvidas sobre commits em repositórios clonados, nomenclatura de branches e a ligação ao repositório remoto, tornaram-se oportunidades de aprendizagem. Foram resolvidas através de testes práticos e pesquisa, permitindo-nos compreender melhor o funcionamento do Git e aplicar boas práticas no desenvolvimento colaborativo.

Este projeto reforçou não só os conhecimentos técnicos, mas também a importância da organização, da comunicação entre colegas e da utilização de ferramentas adequadas para a colaboração em equipa.
