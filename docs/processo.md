# Processo de Desenvolvimento de Software - FisUFBA

A equipe do FisUFBA utilizará um processo de desenvolvimento de software baseado, especialmente, em SCRUM mas também em outras técnicas como descrito a seguir.


O projeto possui um **Kanban**. Tal Kanban possui quatro colunas principais:

* **Product Backlog**, contendo todas as estórias de usuários;
* **Sprint Backlog**, contendo estórias a serem desenvolvidas no sprint atual;
* **Doing**, estórias do sprint atual sendo desenvolvidas no momento;
* **Done**, com estórias que foram finalizadas.


Um sprint terá duração de **uma semana**. Uma reunião ocorrerá entre todos os membros nos domingos a cada final de sprint. Durante essa reunião serão analisados o sprint anterior e uma nova sprint será planejada. A cada sprint uma nova versão do produto será implantada, e feedback será obtido dos stakeholders.

O projeto será dividido em **dois times de desenvolvimento**. Um responsável pelo *front-end* e outro pelo *back-end*. Cada time apresentará dois membros. Um dos membros deve liderar e garantir que a sua porção do projeto está progredindo. Há ainda um quinto membro que deve liderar o projeto como um todo e garantir que ambas as partes estão progredindo.

O projeto fará uso de uma espécie de **desenvolvimento orientado a testes**. Toda feature deve ter testes unitários correspondentes, ou a feature não será considerada concluída.

O projeto fará uso de um sistema de controle de versão. Tal sistema de versionamento será organizado segundo o **modelo de [Git Flow](https://br.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow)**. Nesse modelo há um ramo master, onde qualquer mudança será automaticamente integrada ao servidor de produção, e portanto só deverá conter código funcional. Há um ramo develop, onde todo o código concluído relacionado a um sprint deve estar. Ao final de um sprint, todo o código na develop será mesclado ao código na master. Há ainda um ramo para cada feature sendo desenvolvida, de tal maneira que elas possam ser desenvolvidas independentemente. Quando uma feature estiver concluída (com implementação e testes unitários funcionais), ela deve ser mesclada a develop.


Todo processo de mesclagem deve passar por **revisão** de outros dois desenvolvedores. Um desses desenvolvedores é o líder geral, e o outro o líder local. Se o processo de mesclagem foi solicitado pelo líder geral ou pelo líder local, o segundo par do time local deve substituir o respectivo líder no processo de revisão. Por exemplo, se A é lider geral, B é líder de *back-end*, e C é desenvolvedor *back-end*, e houver um pedido de mesclagem solicitado por C, então A e B devem revisar tal solicitação. Porém, se A solicitar a mesclagem, então B e C devem realizar o processo de revisão.

Os revisores devem garantir que o código mesclado seguem os padrões de projeto e não apresentam problemas adicionais. Caso houver algum problema, o solicitador de mesclagem deve ser informado e este deve realizar a correção necessária. Caso contrário, a solicitação de mesclagem é concluída.



