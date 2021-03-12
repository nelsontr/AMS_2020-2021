<a href="http://fenix.tecnico.ulisboa.pt"><img align="right" src="https://fenix.tecnico.ulisboa.pt/api/bennu-portal/configuration/logo" alt="Fenix Tecnico"></a>

# Project1

### <span style="color:red">WARNINGS</span>

**TODOS** os ficheiros entregues devem ter como prefixo a string "AMS2021_Gxxx_", sendo "xxx" o número do grupo, COM 3 DÍGITOS!!! Por exemplo, para o ficheiro PDF do grupo 12 com o relatório para a primeira entrega, o nome deverá ser "AMS2021_G037_E1.PDF"

## Perguntas

**P:** Haver mais do que um business actor com o mesmo nome é possível? É má pratica? 

**R:** Alternativas - Meter Departamento_Tecnico *ou* Tecnico_TDep.

----

**P:** A agregação do ou nos especialistas está correta? Ou basta as duas setas de atribuição?

**R:** Eu dai interpreto que um especialista *ou* tem um role *ou* outro.

-----

**P:** O CA não devia de ser Business Colaboration??

**R:** Não, está errado se for. O Business Colaboration é como uma role geral, ou seja em que muitos actors podem fazer parte disso (exemplo: Um contrato entre empresas.)

----

**P:** O conector serve presente Especialista de apoio individual está correto??

**R:** A meu ver sim, mas quando falei com o professor das teóricas ele disse que não gostava muito e que faria, para ele, mais sentido um agregação simples.

## Primeiro "Viewport"

* CA
  * CEO
  * CTO
    * TDep
      * Técnicos de manutenção das estações terrestres
    * ODep
      * Especialistas em planeamento de operações
      * Especialistas em aprovisionamento
  * CFO
    * CDep
      * Funcionários especialistas na gestão da relação com os clientes
    * HDeo
    * LDep
      * Técnicos especialistas para apoio ao **CDep** e especialistas para apoio ao **CA**, sendo neste caso esse apoio fornecido a nível individual a cada um desses membros.
    * FDep