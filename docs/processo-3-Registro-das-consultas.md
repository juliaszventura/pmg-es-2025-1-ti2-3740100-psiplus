# 3.3.3 Processo 3 – Registro de Anotações da Consulta

## Registro de Anotações da Consulta  

O processo permite que os profissionais registrem informações importantes sobre as consultas realizadas. Após o atendimento, o médico ou psicólogo pode inserir anotações, revisá-las e armazená-las no sistema. Caso não haja necessidade de anotações, o processo é finalizado diretamente. O sistema garante a organização eficiente dos registros, facilitando o acompanhamento do histórico do paciente.  

![Exemplo de um Modelo BPMN do PROCESSO 4](images/modeloRegistro_Consulta.png)  
![Exemplo de um Modelo BPMN do PROCESSO 4](images/modelagemGestãoDosRegistros.png)  


---

## Detalhamento das atividades  


### **Verificar Existência de Anotações (Gateway Exclusivo – XOR)**  

- **Se houver anotações**, seguir para **Revisar Anotações**.  
- **Se não houver anotações**, seguir diretamente para **Finalizar Registro**.  

---

### **Revisar Anotações**  

| **Campo** | **Tipo** | **Restrições** | **Valor default** |
| --- | --- | --- | --- |
| visualizarAnotacoes | Área de Texto | Somente leitura | Anotações feitas |

| **Comandos** | **Destino** | **Tipo** |
| --- | --- | --- |
| confirmar | Processo "Salvar no Sistema" | default |
| editar | Retornar para "Registrar Dados da Consulta" | action |

---

### **Salvar no Sistema**  

| **Campo** | **Tipo** | **Restrições** | **Valor default** |
| --- | --- | --- | --- |
| status | Texto Automático | Somente leitura | "Salvo com sucesso" |

| **Comandos** | **Destino** | **Tipo** |
| --- | --- | --- |
| ok | Processo "Finalizar Registro" | default |

