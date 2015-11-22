##SOFTWARE VERIFICATION AND VALIDATION

*Testing, bug reports, code inspection, etc.*

---

#####VERIFICATION

*Are we building the product right?*

---

#####VALIDATION

*Are we building the right product?*

---

######*TESTING*


Em *Extreme Programming* ([Modelo de processo de software](https://github.com/DiogoXRP/atom/blob/master/ESOF-docs/SoftwareProcessModel.md) utilizado no **ATOM**) o processo de testes é constante e extremamente importante no desenvolvimento do software pretendido. Um processo exaustivo de *testing* faz com que o tempo de *debug* seja reduzido e ainda aumenta a “confiança” do programador no codigo que desenvolveu. Assim o software desenvolvido será mais coeso e mais adaptável a qualquer tipo de mudanca pretendida pelos utilizadores, visto que passando pelos vários testes criados, o código gerado dá garantias quer ao desenvolvedor/programador quer ao utilizador/cliente que o código desenvolvido está bem estruturado e a realizar os objectivos propostos pelo cliente (*requirements*). 

No processo seguido pelo **ATOM**, é privilegiada a geração de testes o mais cedo possivel. Assim o custo para encontrar e resolver os bugs que surgem será reduzido.
Muitas vezes os testes são gerados antes até de o código ser desenvolvido. Isto dá ao programador e desenvolvedor uma maior clareza sobre o objectivo a atingir (*TDD - Test Driven Development*). 

<dl>
<dt>Segundo Extreme Programming, o processo de desenvolvimento do software ATOM segue as seguintes fases de teste:
</dt>

<dd> Unit testing:

Estes testes são criados pelos programadores e desenvolvedores da aplicação e  têm como objetivo detectar e eliminar qualquer tipo de defeitos funcionais e estruturais desenvolvidos pelos programadores.</dd>

<dd> Acceptance testing:

Testes gerados normalmente com o cliente para garantir que o software está dentro dos objectivos propostos pelo cliente (requirements).</dd>
</dl>

Sendo Extreme Programming um processo que segue as metodologias Agile toda esta fase de testes e de criação de código é revista por varios colaboradores do software desenvolvido o que faz com que o codigo criado seja bem estruturado e perceptivel aos diversos colaboradores.

O **ATOM**, uma vez seguindo o método Extreme Programming, valoriza muito processos de *software inspection*, evitando desta forma o impacto e o custo de possíveis erros e sendo geralmente uma forma mais rápida e eficaz de efetuar a pesquisa desses erros, comparativamente com a realização de testes.

<dl>
<dt>Neste processo, são utilizados vários tipos de reviews, dentro dos quais são de destacar *Refactoring*, *Pair Programming* e *Team Inspection*, processos estes que são os mais utilizados e aqueles que promovem uma maior rapidez e também uma maior partilha de conhecimento entre os vários programadores e desenvolvedores do **ATOM**.</dt>

<dd> Refactoring:
Processo de reestruturação de código, que aumentam a facilidade de revisão do código e reduz a sua complexidade. Esta funcionalidade é crucial num método como Extreme Programming, ou em qualquer outro método incremental, uma vez que facilita imenso a adição de novas funcionalidades ao programa.</dd>

<dd> Pair Programming:
Todo o código é escrito com dois programadores a olhar para um ecrã, e apenas utilizando um teclado e um rato. Cada um dos programadores tem uma tarefa específica neste processo. Um dos parceiros, chamado de driver, escreve o código, enquanto que o outro, o observer, está a fazer revisão do código à medida que este é escrito e pensa também se a estratégia que está a ser seguida será a melhor, dando ideias para melhorar o código.</dd>

<dd> Team Inspection:
Tipo de Software Review no qual o código é revisto pelo programador que escreveu o código e por um ou mais desenvolvedores. Com este tipo de reviews é possível identificar problemas e erros o mais cedo possível e também com maior rapidez. Tal como disse Eric S. Raymond, "Given enough eyeballs, all bugs are shallow" ou seja, se existirem suficientes reviewers, todos os problemas são fácies de resolver.</dd>
</dl>
