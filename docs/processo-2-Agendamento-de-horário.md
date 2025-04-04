### 3.3.2 Processo 2 – Agendamento de horários

O processo de agendamento de horários por parte do paciente se inicia na visualização da agenda atualizada, onde o usuário pode clicar em um botão e ser levado para uma tela de confirmação podendo confirmar ou cancelar a operação.


![Modelo BPMN agendamento](images/diagramaPaciente.png)

![image](https://github.com/user-attachments/assets/43c3f381-9ee9-4376-ad13-da6bceca6519)
![image](https://github.com/user-attachments/assets/0bf1b8e6-d9ca-46c7-bea1-16d2296b6584)
![image](https://github.com/user-attachments/assets/5c5bd77a-ac20-427d-a987-e587cf79dfc9)
![image](https://github.com/user-attachments/assets/3fad1d44-caee-4aba-8e90-185535c0ebb1)




**Visualizar agenda**

| **Comandos**         |  **Destino**                   | **Tipo**          |
| ---                  | ---                            | ---               |
| agendarConsulta                | Abrir popup de agendamento| ---               |
| botaoEmocoes                | Ir para o processo Gestao das emocoes| ---               |


**Selecionar data e hora, Confirmar agendamento**
| **Campo**       | **Tipo**         | **Restrições** | **Valor default** |
| ---             | ---              | ---            | ---               |
| [Nome do campo] | [tipo de dados]  |                |                   |
| dataehora       | Data e Hora      |dd-mm-aaaa, hh:mm|                   |

| **Comandos**         |  **Destino**                   | **Tipo**          |
| ---                  | ---                            | ---               |
| confirmar | Horário é reservado para o paciente | default|
| cancelar| Processo é cancelado |cancel|


**Visualizar agenda atualizada**

| **Comandos**         |  **Destino**                   | **Tipo**          |
| ---                  | ---                            | ---               |
| agendarConsulta                | Abrir popup de agendamento| ---               |
| botaoEmocoes                | Ir para o processo Gestao das emocoes| ---               |
