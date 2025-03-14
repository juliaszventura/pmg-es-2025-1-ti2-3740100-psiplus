### 3.3.4 Processo 4 – Estatísticas e feedback das emoções do indivíduo

O sistema apresenta uma visão de um período selecionado das emoções do paciente, com base nos registros realizados pelo paciente e pelo psicólogo. Com o gráfico é possível realizar comparação entre as visões e também é possível analisar o progresso com o tempo e ter feedbacks das consultas realizadas, o que facilita para o psicólogo proporcionando um melhor acompanhamento e também para o paciente compreender o processo terapêutico.

![Wireframe-Calendario](images/wireframeCalendario.png "Wireframe calendário.")
![Wireframe](images/wireframe-estatisticas.jpeg "Wireframe tela estatísticas.")

![Exemplo de um Modelo BPMN do PROCESSO 4](images/bpmn-estatisticas.png "Modelo BPMN do Processo 4.")


#### Detalhamento das atividades

_Descreva aqui cada uma das propriedades das atividades do processo 4. 
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

**Cadastro de Emoção**

| **Campo**       | **Tipo**         | **Restrições** | **Valor default** |
| ---             | ---              | ---            | ---               |
| emoção_atual    | Seleção única    |  Obrigatório   |   Neutro          |
| observações     | Caixa de Texto   | ---            | Não há observações |

| **Comandos**         |  **Destino**                   | **Tipo** |
| ---                  | ---                            | ---               |
| cadastrar            | Adiciona o registro no banco   | default           |
| cancelar             | Cancela o registro             | cancel            |


**Alteração de visualização do gráfico**

| **Campo**       | **Tipo**         | **Restrições** | **Valor default** |
| ---             | ---              | ---            | ---               |
| Alteração de Visualização | Seleção única  |  Opcional              |   Semanal               |
