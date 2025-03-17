### 3.3.2 Processo 2 – Cadastro e Gestão do paciente

Gestão do Paciente e Histórico Cínico: A gestão de pacientes e históricos clínicos em clínicas de psicologia enfrenta desafios como registros descentralizados, dificuldades de acesso às informações e processos manuais suscetíveis a erros. A digitalização completa do processo permite maior organização, reduz burocracias e melhora a continuidade do tratamento. Um sistema centralizado e automatizado possibilita um cadastro mais eficiente, facilitando atualizações e acesso rápido ao histórico clínico. Além disso, a inclusão de um módulo para solicitação de histórico pelos pacientes proporciona mais autonomia, garantindo um atendimento mais ágil e eficiente.

![Exemplo de um Modelo BPMN do PROCESSO 2](images/wireframe%20gest%C3%A3o%20das%20sess%C3%B5es.png).")


#### Detalhamento das atividades

_Descreva aqui cada uma das propriedades das atividades do processo 2. 
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

**selecionar consulta, pessoa ou data**

| **Campo**       | **Tipo**         | **Restrições** | **Valor default** |
| ---             | ---              | ---            | ---               |
| Tipo de pesquisa| Seleção única    |  Obrigatório   |    Pessoa         |
|  Pesquisar      |  Área de texto  |   Obrigatório  |    Null           |

| **Comandos**         |  **Destino**                   | **Tipo** |
| ---                  | ---                            | ---               |
| Selecionar pessoa    | Consultas da pessoa            | Null              |


**Nome da atividade 2**

| **Campo**       | **Tipo**         | **Restrições** | **Valor default** |
| ---             | ---              | ---            | ---               |
| Anotações       | Caixa de texto   | Confirmação da identidade| Null    |

