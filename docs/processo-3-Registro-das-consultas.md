### 3.3.3 Processo 3 – Registro das consultas

**Registro das consultas:** O processo de agendamento de consultas permite que psicólogos cadastrem seus horários disponíveis e ocupados, enquanto os pacientes podem visualizar os horários livres e agendar uma consulta diretamente pela plataforma. O sistema facilita a organização do tempo dos psicólogos e oferece aos pacientes uma maneira simples e eficiente de marcar consultas, garantindo uma gestão otimizada de horários e maior conveniência para ambos os lados.

![Exemplo de um Modelo BPMN do PROCESSO 3](images/ "Modelo BPMN do Processo 3.") 


#### Detalhamento das atividades

**Efetuar Login**

| **Campo**       | **Tipo**         | **Restrições** | **Valor default** |
| ---             | ---              | ---            | ---               |
| login           | Caixa de Texto   | formato de e-mail |                |
| senha           | Caixa de Texto   | mínimo de 8 caracteres |           |

| **Comandos**         |  **Destino**                   | **Tipo** |
| ---                  | ---                            | ---               |
| entrar               | Fim do Processo Efetuar Login           | default           |
| cadastrar            | Início do proceso de cadastro  |                   |


**Cadastrar horário vago**

| **Campo**       | **Tipo**         | **Restrições** | **Valor default** |
| ---             | ---              | ---            | ---               |
| [Nome do campo] | [tipo de dados]  |                |                   |
| dataehora       | Data e Hora      |dd-mm-aaaa, hh:mm|                   |

| **Comandos**         |  **Destino**                   | **Tipo**          |
| ---                  | ---                            | ---               |
| confirmar | Fim do Processo Cadastrar horário vago  | default|
| cancelar| Fim do Processo Cadastrar horário vago|cancel|


**Cadastrar horário ocupado**
| **Campo**       | **Tipo**         | **Restrições** | **Valor default** |
| ---             | ---              | ---            | ---               |
| nomepaciente       | Caixa de texto      |---| nome                   |
| dataehora       | Data e Hora      |dd-mm-aaaa, hh:mm|    

| **Comandos**         |  **Destino**                   | **Tipo**          |
| ---                  | ---                            | ---               |
| confirmar | Fim do Processo Cadastrar horário ocupado  | default|
| cancelar| Fim do Processo Cadastrar horário ocupado|cancel|


**Ocupar horário disponível**
 **Campo**       | **Tipo**         | **Restrições** | **Valor default** |
| ---             | ---              | ---            | ---               |
| selecionarhorario      | Seleção única      |---|                  |

| **Comandos**         |  **Destino**                   | **Tipo**          |
| ---                  | ---                            | ---               |
| confirmar | Fim do Processo Ocupar horário disponível  | default|
| cancelar| Fim do Processo Ocupar horário disponível|cancel|
