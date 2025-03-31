### 3.3.5 Processo 5 – Gestão do Registro de Anotações da Consulta

O processo permite que os profissionais consultem registros, informações importantes sobre as consultas realizadas. O sistema garante a organização eficiente dos registros, facilitando o acompanhamento do histórico do paciente.  


![Exemplo de um Modelo BPMN do PROCESSO 5](images/wireframe-1-Gestao-Registros-Consultas.png)

![Exemplo de um Modelo BPMN do PROCESSO 5](images/wireframe-2-Gestao-Registros-Consultas.png)

![Exemplo de um Modelo BPMN do PROCESSO 5](images/wireframe-3-Gestao-Registros-Consultas.png)


![Exemplo de um Modelo BPMN do PROCESSO 5](images/bpmnGestaoRegistroConsultas.png)  



## Detalhamento das atividades de Gestão de registros. 

---

### **Escolher o tipo de pesquisa (Paciente ou Consulta)**  

| **Campo** | **Tipo** | **Restrições** | **Valor default** |
| --- | --- | --- | --- |
| o que você procura | Seleção única | obrigatório | - |

### **Pesquisar**  

| **Campo** | **Tipo** | **Restrições** | **Valor default** |
| --- | --- | --- | --- |
| Pesquisar | Área de texto | obrigatório | - |

| **Comandos** | **Destino** | **Tipo** |
| --- | --- | --- |
| Icone pesquisar | Processo "Exibir resultados filtrados" | Tabela |
---

### **Selecionar um dos resultados exibidos**  

| **Comandos** | **Destino** | **Tipo** |
| --- | --- | --- |
| Selecionar | Gráficos e anotações | Tabela |

