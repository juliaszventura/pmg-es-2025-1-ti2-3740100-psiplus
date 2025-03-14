### 3.3.5 Processo 5 – Agendamento e Registro de Consultas

O sistema permite que o psicólogo registre consultas agendadas, permitindo que o paciente confirme, reagende ou cancele o compromisso. No momento da consulta, o psicólogo pode adicionar anotações ao atendimento e salvar o histórico do paciente para futuras referências.

![Exemplo de um Modelo BPMN do PROCESSO 5](images/modeloRegistro_Consulta.png)


**Cadastro de Consulta**

| **Campo**          | **Tipo**         | **Restrições**  | **Valor default**  |
| ---               | ---              | ---             | ---                |
| paciente          | Seleção única    | Obrigatório     | ---                |
| data_consulta     | Data e Hora      | Obrigatório     | ---                |
| status_consulta   | Seleção única    | Obrigatório     | Agendada           |

| **Comandos**      | **Destino**                     | **Tipo**   |
| ---              | ---                              | ---        |
| agendar         | Registra a consulta no sistema  | default    |
| cancelar        | Cancela a operação              | cancel     |

**Registro de Atendimento**

| **Campo**       | **Tipo**       | **Restrições**  | **Valor default**  |
| ---             | ---            | ---             | ---                |
| anotações       | Área de Texto  | Opcional        | Não há anotações   |
| anexos         | Arquivo        | Opcional        | ---                |

| **Comandos**     | **Destino**                     | **Tipo**   |
| ---              | ---                              | ---        |
| salvar          | Adiciona registro ao histórico  | default    |
| cancelar        | Cancela a operação              | cancel     |

