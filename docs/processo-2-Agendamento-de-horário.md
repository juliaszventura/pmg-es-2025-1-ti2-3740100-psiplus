### 3.3.2 Processo 2 – Agendamento de horários

O processo de agendamento de horários por parte do paciente se inicia na visualização da agenda atualizada, onde o usuário pode clicar em um botão e ser levado para uma tela de confirmação podendo confirmar ou cancelar a operação.


![Modelo BPMN agendamento](images/diagramaAgendamento.png)

![image](https://github.com/user-attachments/assets/43c3f381-9ee9-4376-ad13-da6bceca6519)


**Visualizar agenda**

| **Campo**       | **Tipo**         | **Restrições** | **Valor default** |
| ---             | ---              | ---            | ---               |
| [Nome do campo] | [tipo de dados]  |                |                   |

| **Comandos**         |  **Destino**                   | **Tipo**          |
| ---                  | ---                            | ---               |
| agendarConsulta                | Abrir popup de agendamento| ---               |
| botaoEmocoes                | Ir para o processo Gestao das emocoes| ---               |


**Agendamento feito pelo paciente**
| **Campo**       | **Tipo**         | **Restrições** | **Valor default** |
| ---             | ---              | ---            | ---               |
| [Nome do campo] | [tipo de dados]  |                |                   |
| dataehora       | Data e Hora      |dd-mm-aaaa, hh:mm|                   |

| **Comandos**         |  **Destino**                   | **Tipo**          |
| ---                  | ---                            | ---               |
| confirmar | Horário é reservado para o paciente | default|
| cancelar| Processo é cancelado |cancel|
