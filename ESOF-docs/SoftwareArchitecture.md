###SOFTWARE ARCHITECTURE

Como resposta a este tópico, foram desenhados quatro diagramas, sendo estes os correspondentes ao "4+1 view model of software architecture", contudo o [*diagrama de casos de utilização*](https://raw.githubusercontent.com/DiogoXRP/atom/master/ESOF-docs/AtomUseCaseDiagram.jpg) foi desenhado na 2ª **recitation**.

Foi desenvolvido um diagrama adicional para além dos quatro propostos, podendo este ser chamado de [*Atom dependencies to execute and run*](https://raw.githubusercontent.com/DiogoXRP/atom/master/ESOF-docs/AtomDependenciesDiagram.jpg). Para a realização deste diagrama foi necessário recorrer a uma **_utility_** disponível na linha de comandos "Cross Tools" do **Visual Studio 2013**. Para tal foi corrida a mesma linha de comandos dentro da pasta do executável da aplicação **_Atom_** ("atom.exe"). A **_utility_** usada então para o efeito foi:

*dumpbin /dependents atom.exe*

Sendo que esta, lista todas as *dependencies*, tais como dynamic link libraries ([DLL's](https://support.microsoft.com/en-us/kb/815065)), ficheiros .drv ([.drv files](http://file.org/extension/drv)) e .cpl ([.cpl files](https://support.microsoft.com/en-us/kb/149648)), necessárias à execução da aplicação **_Atom_** bem como ao seu funcionamento.

#####[DEPLOYMENT DIAGRAM](https://raw.githubusercontent.com/DiogoXRP/atom/master/ESOF-docs/AtomOriginalDeploymentDiagram.jpg)

Este diagrama mostra a arquitetura da aplicação **_Atom_**, onde para tal é representada a distribuição (*deployment*) de artefactos (software) para alvos de distribuição (*deployment targets*) denominados geralmente por nós (*nodes*).

#####[COMPONENT DIAGRAM](https://raw.githubusercontent.com/DiogoXRP/atom/master/ESOF-docs/AtomComponentDiagram.jpg)

Este diagrama mostra os componentes (*components - logical or physical*), interfaces necessárias e providenciadas (*interfaces*), portas (*ports*), bem como a relação entre elas.

#####[ATIVITY DIAGRAM](https://raw.githubusercontent.com/DiogoXRP/atom/master/ESOF-docs/AtomAtivityDiagram.jpg)

Este diagrama é um diagrama de comportamento UML (*behavior UML*) pois demonstra o controlo do fluxo (*flow of control*) ou o fluxo de um dado objeto (*object flow*), dando para tal ênfase na sequência e condições do fluxo.
