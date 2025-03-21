### 3.3.1 Processo 1 – Cadastro e Gestão da agenda



![Modelo BPMN agendamento](images/diagramaAgendamento.png)

**Cadastrar horário**

| **Campo**       | **Tipo**         | **Restrições** | **Valor default** |
| ---             | ---              | ---            | ---               |
| [Nome do campo] | [tipo de dados]  |                |                   |
| dataehora       | Data e Hora      |dd-mm-aaaa, hh:mm|                   |
| seleçãopaciente       | Seleção única     ||                   |
| horarioocupado       | Seleção única     ||                   |
| horariolivre       | Seleção única     ||                   |

| **Comandos**         |  **Destino**                   | **Tipo**          |
| ---                  | ---                            | ---               |
| criarpaciente                | Enviar para Processo Cadastar Paciente| ---               |
| confirmar | Fim do Processo Cadastrar horário| default|
| cancelar| Fim do Processo Cadastrar horário|cancel|


**Agendamento feito pelo paciente**
| **Campo**       | **Tipo**         | **Restrições** | **Valor default** |
| ---             | ---              | ---            | ---               |
| [Nome do campo] | [tipo de dados]  |                |                   |
| dataehora       | Data e Hora      |dd-mm-aaaa, hh:mm|                   |

| **Comandos**         |  **Destino**                   | **Tipo**          |
| ---                  | ---                            | ---               |
| confirmar | Horário é reservado para o paciente | default|
| cancelar| Processo é cancelado |cancel|
