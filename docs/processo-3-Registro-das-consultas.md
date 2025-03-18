### 3.3.3 Processo 3 – Registro das consultas

**Registro das consultas:** O processo de agendamento de consultas permite que psicólogos cadastrem seus horários disponíveis e ocupados, enquanto os pacientes podem visualizar os horários livres e agendar uma consulta diretamente pela plataforma. O sistema facilita a organização do tempo dos psicólogos e oferece aos pacientes uma maneira simples e eficiente de marcar consultas, garantindo uma gestão otimizada de horários e maior conveniência para ambos os lados.

![Exemplo de um Modelo BPMN do PROCESSO 3](images/ "Modelo BPMN do Processo 3.") 


#### Detalhamento das atividades

**Cadastro de paciente**

| **Campo**       | **Tipo**         | **Restrições** | **Valor default** |
| ---             | ---              | ----           | ---               |
| Nome            | Caixa de texto   | Obrigatório    | -                 |
| Data de Nascimento  | Data                 | Obrigatório (dd-mm-aaaa)               | -                  |
| Telefone           | Número   | Obrigatório, formato (XX) XXXXX-XXXX | -               |
| Gênero           | Seleção única   | Masculino/Feminino/Outro | -               |
| CPF          | Caixa de Texto   | Formato: 000.000.000-00 | -          |
| E-mail          | Caixa de Texto   | Formato de e-mail válido | -          |
| Endereço           | Área de Texto   | Opcional | -               |
| Observações          | Área de Texto   | Opcional | -          |

| **Comandos**         |  **Destino**                   | **Tipo** |
| ---                  | ---                            | ---               |
| Salvar               | Confirma o cadastro e armazena os dados              | default           |
| Cancelar            | Descarta a ação e retorna à tela inicial  | Cancel                  |


**Atualização de Dados do Paciente**

| **Campo**       | **Tipo**         | **Restrições** | **Valor default** |
| ---             | ---              | ----           | ---               |
| Nome            | Caixa de texto   | Editável    | -                 |
| Data de Nascimento  | Data                 | Editável (dd-mm-aaaa)               | -                  |
| Gênero           | Seleção única   | Masculino/Feminino/Outro | -               |
| Telefone           | Número   | Editável, formato (XX) XXXXX-XXXX | -               |
| E-mail          | Caixa de Texto   | Formato de e-mail válido | -          |
| Endereço           | Área de Texto   | Opcional | -               |
| Observações          | Área de Texto   | Opcional | -          |

| **Comandos**         |  **Destino**                   | **Tipo** |
| ---                  | ---                            | ---               |
| Atualizar               | Confirma as alterações              | default           |
| Cancelar            | Descarta mudanças  | cancel                  |


