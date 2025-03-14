### 3.3.3 Processo 3 – Gestão do Paciente e Histórico Clínico

**Gestão do Paciente e Histórico Cínico:** A gestão de pacientes e históricos clínicos em clínicas de psicologia enfrenta desafios como registros descentralizados, dificuldades de acesso às informações e processos manuais suscetíveis a erros. A digitalização completa do processo permite maior organização, reduz burocracias e melhora a continuidade do tratamento. Um sistema centralizado e automatizado possibilita um cadastro mais eficiente, facilitando atualizações e acesso rápido ao histórico clínico. Além disso, a inclusão de um módulo para solicitação de histórico pelos pacientes proporciona mais autonomia, garantindo um atendimento mais ágil e eficiente.

![Exemplo de um Modelo BPMN do PROCESSO 3](images/process.png "Modelo BPMN do Processo 3.")


#### Detalhamento das atividades

_Descreva aqui cada uma das propriedades das atividades do processo 3. 
Devem estar relacionadas com o modelo de processo apresentado anteriormente._

_Os tipos de dados a serem utilizados são:_

_* **Área de texto** - campo texto de múltiplas linhas_

_* **Caixa de texto** - campo texto de uma linha_

_* **Número** - campo numérico_

_* **Data** - campo do tipo data (dd-mm-aaaa)_

_* **Hora** - campo do tipo hora (hh:mm:ss)_

_* **Data e Hora** - campo do tipo data e hora (dd-mm-aaaa, hh:mm:ss)_

_* **Imagem** - campo contendo uma imagem_

_* **Seleção única** - campo com várias opções de valores que são mutuamente exclusivas (tradicional radio button ou combobox)_

_* **Seleção múltipla** - campo com várias opções que podem ser selecionadas mutuamente (tradicional checkbox ou listbox)_

_* **Arquivo** - campo de upload de documento_

_* **Link** - campo que armazena uma URL_

_* **Tabela** - campo formado por uma matriz de valores_

**Cadastro de paciente**

| **Campo**       | **Tipo**         | **Restrições** | **Valor default** |
| ---             | ---              | ----           | ---               |
| Nome            | Caixa de texto   | Obrigatório    | -                 |
| Data de Nascimento  | Data                 | Obrigatório (dd-mm-aaaa)               | -                  |
| Telefone           | Número   | Obrigatório, formato (XX) XXXXX-XXXX | -               |
| E-mail          | Caixa de Texto   | Formato de e-mail válido | -          |
| Endereço           | Área de Texto   | Opcional | -               |
| Observações          | Área de Texto   | Opcional | -          |

| **Comandos**         |  **Destino**                   | **Tipo** |
| ---                  | ---                            | ---               |
| Salvar               | Confirma o cadastro e armazena os dados              | default           |
| Cancelar            | Descarta a ação e retorna à tela inicial  | default                  |


**Atualização de Dados do Paciente**

| **Campo**       | **Tipo**         | **Restrições** | **Valor default** |
| ---             | ---              | ----           | ---               |
| Nome            | Caixa de texto   | Editável    | -                 |
| Data de Nascimento  | Data                 | Editável (dd-mm-aaaa)               | -                  |
| Telefone           | Número   | Editável, formato (XX) XXXXX-XXXX | -               |
| E-mail          | Caixa de Texto   | Formato de e-mail válido | -          |
| Endereço           | Área de Texto   | Opcional | -               |
| Observações          | Área de Texto   | Opcional | -          |

| **Comandos**         |  **Destino**                   | **Tipo** |
| ---                  | ---                            | ---               |
| Atualizar               | Confirma as alterações              | default           |
| Cancelar            | Descarta mudanças  | cancel                  |

**Consulta ao Histórico Clínico**

| **Campo**       | **Tipo**         | **Restrições** | **Valor default** |
| ---             | ---              | ----           | ---               |
| Data da Consulta            | Data   | Obrigatório    | -                 |
| Anotações  | Área de Texto                 | Somente leitura               | -                  |
| Diagnóstico           | Área de Texto   | Somente leitura | -               |

| **Comandos**         |  **Destino**                   | **Tipo** |
| ---                  | ---                            | ---               |
| Visualizar               | Exibe o histórico do paciente              | default           |
| Fechar            | Sai da tela sem alterar dados  | cancel                  |

**Solicitação de Histórico pelo Paciente**

| **Campo**       | **Tipo**         | **Restrições** | **Valor default** |
| ---             | ---              | ----           | ---               |
| Justificativa   | Área de Texto   | Obrigatório    | -                 |

| **Comandos**         |  **Destino**                   | **Tipo** |
| ---                  | ---                            | ---               |
| Enviar               | Envia a solicitação ao psicólogo              | default           |
| Cancelar            | Cancela a solicitação  | cancel                  |

**Liberação do Histórico para o Paciente**

| **Campo**       | **Tipo**         | **Restrições** | **Valor default** |
| ---             | ---              | ----           | ---               |
| Histórico do Paciente   | Área de Texto   | Somente leitura   | -                 |

| **Comandos**         |  **Destino**                   | **Tipo** |
| ---                  | ---                            | ---               |
| Aprovar               | Disponibiliza o histórico ao paciente              | default           |
| Recusar            | Notifica paciente da recusa  | cancel                  |

