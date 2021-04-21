<a href="http://fenix.tecnico.ulisboa.pt"><img align="right" src="https://fenix.tecnico.ulisboa.pt/api/bennu-portal/configuration/logo" alt="Fenix Tecnico"></a>

# AMS_20-21 - Project02

**Diagramas a realizar:**

* [#1](#bpmn---processo-de-proposta-a-um-pedido-e-de-celebração-de-contrato) - `BPMN` - Processo de proposta a um pedido e de celebração de contrato;
* [#2](#bpmn---processo-de-intervenção) - `BPMN` - Processo de intervenção numa estação;
* [#3]() - `UML` - Casos de uso da Aplicação *Satis*;
* [#4]() - `Lingua Natural` - Descrição estruturada.

## BPMN - Processo de proposta a um pedido e de celebração de contrato

### Dúvidas

#### Respondidas

​	**Q:** A forma como temos a resposta em simultâneo é a adequada? Ou existe uma maneira mais adequada de ser feita?

​	**A:** É sequencial - meter a tarefa como sequencial

---

​	**Q:** Precisamos de fazer o mesmo que fizemos no simultâneo no envio das propostas?

​	**A:** *Não perguntado*

---

​	**Q:** Em termos de o cliente responder dentro de um certo tempo ás criticas do LDep e do TDep, a maneira como temos corresponde a essa interpretação??

​	**A:** Interpretações diferentes, precisamos de interpretar os `Pareceres Juridicos` e os `Pareceres Legais`

---

​	**Q:** Qual a diferença entre fazer como está no cliente e no TDep?

​	**A:** O nosso diagrama é um processo privado, pelo que tudo (exceto o Cliente) deve estar uma lane.

---

​	**Q:** Como informar o responsável quando o LDep/TDep demoram mais do que 24 horas a responder?

​	**A:** Há um exemplo algures em 2019

---
​	**Q:** Qual a diferença entre `Evento de envio` e `Tarefa de envio`?

​	**A:** O evento não pertence a ninguém, ou seja o enviar mensagem não tem nenhuma atividade por trás. A tarefa de enviar mensagem já indica que há um trabalho por trás antes de enviar. Por exemplo escrever um mail para a professora a dizer que queria ir ao horário de dúvidas: tarefa porque tive de elaborar e escrever o mail. Se fosse uma cena automática de enviar já era um evento.

---

​ **Q:** Como fazer as 24horas do relatório? Será que poderíamos fazer uma tarefa com ciclo?

​ **A:** Temos de por de duas maneiras por causa das desistencias em paralelo

---

​ **Q:** Podemos meter cores? \^_^

​ **A:** Podemos 

---

​ **Q:** Será que podemos ter uma tarefa de envio sem receber do outro lado?

​ **A:** Podemos porque estamos na mesma pool; eventos de envios mais necessarios para pools diferentes

---

​ **Q:** Data Objects - Como é que os ligamos?

​ **A:** Data store para registar porque todos os pareceres e etc têm de ser registados

---

​ **Q:** Todos têm acesso a um relatório feito por terceiros? 

​ **A:** Com data store sim

---

#### Resolução

![Diagrama01](diagram_1.png)



## BPMN - Processo de intervenção

#### Dúvidas

​	**Q:** O ODep pode rever o plano de entregas com o operador logístico ou alterar o plano de viagens. Não estou a perceber muito bem esta parte. Pelo menos a parte na equipa TDep pode ser elaborada da forma que está?

​	**A:** (...)

---

​	**Q:** O TDep elabora um relatório para enviar ao CTO no fim de cada intervenção, seja esta mensal ou de avaria, certo? Porém o CTO só envia um relatório para o CA quando são intervenções mensais, certo?

​	**A:** (...)

---

#### Resolução

![Diagrama02](diagram_2.png)


### Casos de uso da Aplicação *Satis*

#### Resolução

![Diagrama03](diagrama_3.jpg)
