###REQUIREMENTS ELICITATION

Como resposta a este tópico, foram desenhados quatro diagramas, sendo estes os correspondentes ao "4+1 view model of software architecture", contudo o [*diagrama de casos de utilização*](https://raw.githubusercontent.com/DiogoXRP/atom/master/ESOF-docs/AtomUseCaseDiagram.jpg) foi desenhado na 2ª **recitation**.

Um destes quatro diagramas é o [*diagrama de "deployment"*](https://raw.githubusercontent.com/DiogoXRP/atom/master/ESOF-docs/AtomDeploymentDiagram.jpg). Para este diagrama foi necessário recorrer a uma **_utility_** disponível na linha de comandos "Cross Tools" do **Visual Studio 2013**. Para tal foi corrida linha de comandos dentro da pasta do executável da aplicação **_Atom_** ("atom.exe"). A **_utility_** usada então para o efeito foi:

*dumpbin /dependents atom.exe*

Sendo que esta, lista todas as *dependencies*, tais como dynamic link libraries ([DLL's](https://support.microsoft.com/en-us/kb/815065)), ficheiros .drv ([.drv files](http://file.org/extension/drv)) e .cpl ([.cpl files](https://support.microsoft.com/en-us/kb/149648)), necessárias à execução da aplicação **_Atom_** bem como ao seu funcionamento.
