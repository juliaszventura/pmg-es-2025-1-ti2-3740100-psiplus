### 3.3.5 Processo 5 – Agendamento e Registro de Consultas

O sistema permite que o psicólogo registre consultas agendadas, permitindo que o paciente confirme, reagende ou cancele o compromisso. No momento da consulta, o psicólogo pode adicionar anotações ao atendimento e salvar o histórico do paciente para futuras referências.

![Exemplo de um Modelo BPMN do PROCESSO 5](images/modeloRegistro_Consulta.png")

#### Detalhamento das atividades

_Descreva aqui cada uma das propriedades das atividades do processo 5.
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

