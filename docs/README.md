# PSIPLUS


**Nico Jobski Andrade, jobskiandrade@gmail.com**

**Júlia de Souza Ventura, juliavt403@gmail.com**

**Rafael Rocha Caldeira Brant, rafaelrbrant07@gmail.com**

**Ana Luiza de Freitas Rodrigues, analuizafreitas12@yahoo.com.br**

**Kayke Emanoel de Souza Santos, kaykeeman@gmail.com**

**Carlos Eduardo Sousa Santos, cadusantos9000@gmail.com**

---

Professores:

**Michelle Hanne Soares de Andrade**

**Danilo de Quadra Maia Filho**

**Joana Gabriela Ribeiro de Souza**

---

_Curso de Engenharia de Software_

_Instituto de Informática e Ciências Exatas – Pontifícia Universidade Católica de Minas Gerais (PUC MINAS), Belo Horizonte – MG – Brasil_

---

Esse projeto visa desenvolver uma plataforma online para psicólogos, centralizando todas as funcionalidades essenciais em um só lugar. O sistema permitirá o agendamento de consultas, controle dos pacientes e o registro do estado emocional deles, proporcionando mais organização e eficiência. O objetivo é otimizar a rotina dos profissionais e aprimorar a experiência dos pacientes, eliminando a necessidade de múltiplas ferramentas e garantindo um atendimento mais fluido e integrado.

---


## 1. Introdução

No mundo digital de hoje, até os consultórios de psicologia precisam se modernizar. Muitos profissionais ainda dependem de métodos manuais ou de sistemas desconexos para agendar, gerenciar consultas e acompanhar o bem-estar dos pacientes. Pensando nisso, surge a proposta de desenvolver uma plataforma integrada que reúne todas essas funcionalidades em um só lugar, tornando o dia a dia dos psicólogos muito mais prático.

### 1.1 Contextualização

Atualmente, é comum que os psicólogos utilizem diversos sistemas separados para realizar suas atividades diárias, como plataformas para preenchimento de cadastros e formulários (Google Forms), ferramentas para agendamento de consultas(Zenklub, Virtude), agendas de gestão virtuais (PsicologiaNET, ClinicaWEB), além de diferentes métodos para anotação e avaliação dos pacientes. Essa fragmentação de processos pode gerar desafios na gestão eficiente das informações e no acompanhamento do progresso dos pacientes.
Diante desse cenário, surge uma oportunidade para integrar e potencializar essas funcionalidades, criando uma solução que unifique esses processos. Além disso, visamos desenvolver novas abordagens para avaliação psicológica, oferecendo recursos como a apresentação de estatísticas e dados detalhados sobre o estado de cada paciente, facilitando a gestão do trabalho do psicólogo e promovendo uma visão mais clara e completa sobre os casos tratados.

### 1.2 Problema

A falta de confiança dos pacientes em falar sobre seus sentimentos é um dos desafios mais complexos enfrentados pelos psicólogos no exercício da psicoterapia. A relação terapêutica 
é construída sobre uma base de confiança mútua, e, quando essa confiança não é estabelecida,o progresso do tratamento pode ser severamente prejudicado. Estudos indicam que muitos 
pacientes enfrentam dificuldades em expressar suas emoções, o que pode comprometer a eficácia do tratamento[1.6]. Pensando nisso nós da PSI+ criamos uma solução 
para que essas ocasiões possam ser contornadas, nosso sistema conta comum calendario de emocões onde o paciente possa se expressar mais confortavelmente, e assim
o psicólogo pode ter acesso ao que o paciente sente e fazer as sessões serem mais produtivas.

A gestão eficiente das datas de consultas e dos pacientes cadastrados é um desafio significativo para psicólogos, impactando diretamente na qualidade do atendimento e no 
andamento dos tratamentos. A falta de organização pode levar a atrasos no atendimento e a falta do paciente na consulta, comprometendo a eficácia das intervenções terapêuticas[1.7]. Nosso sistema apresenta uma excelente ferramenta paraque esses problemas sejam evitados, como por exemplo: mandando um email e uma mensagem para
o paciente um dia antes de sua consulta, visando confirmar sua presença podendo dar continuidade ou desmarcar a sua consulta caso ele queira.

### 1.3 Objetivo geral

O objetivo geral deste trabalho é desenvolver o PSI+, um sistema de gestão digital para psicólogos e pacientes que centralize as principais funcionalidades necessárias para uma prática clínica eficiente e organizada. A plataforma tem como foco a organização da agenda profissional, oferecendo um sistema de agendamento simples e intuitivo, além de um canal de comunicação seguro entre psicólogos e pacientes. Além disso, o PSI+ permitirá o registro diário das emoções dos pacientes, facilitando um acompanhamento mais próximo por parte do profissional. O objetivo é criar uma solução acessível, intuitiva e prática, tornando a gestão das consultas mais eficiente e a experiência do usuário mais fluida e livre de complicações.

#### 1.3.1 Objetivos específicos

Os objetivos específicos deste trabalho incluem a criação de um sistema de agendamento simples e intuitivo, além do estabelecimento de um canal de comunicação eficaz entre psicólogos e pacientes. Também busca-se implementar um módulo para o registro e monitoramento dos sentimentos dos pacientes, garantindo um acompanhamento contínuo. Além disso, o sistema deve proporcionar uma experiência de uso agradável, priorizando a acessibilidade e a facilidade de navegação. Por fim, pretende-se oferecer uma gestão eficiente das consultas do consultório, permitindo o controle preciso dos horários, o registro do histórico de atendimentos e a organização das sessões de maneira prática e livre de erros.

### 1.4 Justificativas

A gestão de práticas psicológicas enfrenta desafios significativos, como a desorganização da agenda, dificuldades no acompanhamento das emoções dos pacientes e comunicação limitada entre sessões. Esses problemas impactam tanto os profissionais quanto os pacientes, comprometendo a qualidade do atendimento e a continuidade do tratamento.

Um dos desafios mais complexos enfrentados pelos psicólogos é a dificuldade dos pacientes em expressar seus sentimentos. A relação terapêutica é baseada na confiança mútua e, quando essa confiança não é estabelecida, o progresso do tratamento pode ser prejudicado. Estudos indicam que muitos pacientes têm dificuldades em comunicar suas emoções, o que pode comprometer a eficácia da terapia. Pensando nisso, o projeto Psi+ propõe uma solução inovadora: um calendário de emoções. Esse recurso permitirá que os pacientes registrem seus sentimentos de forma confortável e contínua, proporcionando ao psicólogo uma visão mais ampla do estado emocional do paciente e tornando as sessões mais produtivas.

Além disso, a gestão eficiente das consultas é outro grande desafio para os psicólogos, impactando diretamente a qualidade do atendimento. A falta de organização pode resultar em atrasos, ausências e dificuldades na continuidade do tratamento. Para mitigar esse problema, o sistema Psi+ incluirá uma ferramenta automatizada de notificações, enviando e-mails e mensagens aos pacientes um dia antes da consulta para confirmação ou cancelamento, garantindo um melhor aproveitamento da agenda do profissional.

Este trabalho se justifica pela crescente demanda por soluções tecnológicas na área da saúde mental, especialmente na psicologia, e pela necessidade de um sistema que otimize o gerenciamento tanto para o profissional quanto para o paciente. A proposta de um sistema digital de gestão possibilita a integração do agendamento, da comunicação e do acompanhamento emocional em uma única plataforma, simplificando o dia a dia do psicólogo e promovendo um atendimento mais organizado e eficiente. Além disso, o uso da tecnologia como aliada no processo terapêutico torna as informações mais acessíveis e gerenciáveis, contribuindo para uma experiência mais completa e satisfatória para ambas as partes.

## 2. Participantes do processo

### 2.1. Psicólogo 

- Conseguir cadastrar todos os seus clientes em uma única plataforma
- Poder agendar as consultas em um calendário virtual
- Ter mais organização com os horários das consultas
- Ter uma visão geral da agenda e das sessões marcadas, remarcadas ou canceladas
- Otimizar o tempo e reduzir erros na gestão da clínica
- Ter um registro organizado do histórico emocional dos pacientes
- Fornecer um serviço de melhor qualidade para seus clientes
- Acompanhar a evolução dos pacientes de forma mais estruturada
- Manter anotações e registros seguros sobre as sessões
- Utilizar ferramentas que a ajudem a monitorar o progresso terapêutico

### 2.2. Paciente

- Agendar e remarcar consultas de forma prática e rápida
- Registrar emoções e eventos diários para compartilhar com o psicólogo
- Ter acesso ao histórico das próprias emoções e identificar padrões emocionais
- Comunicar-se de maneira segura e pontual com o psicólogo entre as sessões
- Sentir-se mais ativo no próprio processo terapêutico através do acompanhamento digital
- Garantir que suas informações e registros estejam protegidos e acessíveis quando necessário

## 3. Modelagem do processo de negócio

### 3.1. Análise da situação atual

Atualmente, muitos psicólogos enfrentam desafios na gestão de suas práticas clínicas devido à ausência de sistemas integrados que facilitem o agendamento de consultas, o acompanhamento do estado emocional dos pacientes e a comunicação eficiente entre sessões. Muitos profissionais ainda dependem de métodos manuais ou de sistemas desconexos, o que pode levar a agendamentos confusos, dificuldades no monitoramento contínuo dos pacientes e limitações na comunicação, impactando a qualidade do atendimento e a eficiência do processo terapêutico.​

**Cadastro e Gestão da agenda (Psicólogo):** 

**Cadastro e Gestão do paciente (Psicólogo):**

**Registro das consultas (Psicólogo):** 

**Registro das emoções e calendário (Paciente):** 

### 3.2. Descrição geral da proposta de solução

A proposta do PSI+ é desenvolver uma plataforma online que centralize as principais funcionalidades necessárias para a prática psicológica em um único ambiente digital. O sistema permitirá o agendamento de consultas de forma simples e intuitiva, o registro e monitoramento contínuo das emoções dos pacientes, e estabelecerá um canal de comunicação seguro entre psicólogos e pacientes. Além disso, a plataforma oferecerá recursos para a gestão eficiente das consultas, permitindo o controle de horários, histórico e organização das sessões de forma prática e sem erros. Ao integrar essas funcionalidades, o PSI+ busca otimizar a rotina dos profissionais de psicologia e aprimorar a experiência dos pacientes, promovendo um atendimento mais organizado, eficiente e centrado nas necessidades individuais.​

**Cadastro e Gestão da agenda (Psicólogo):** 

**Cadastro e Gestão do paciente (Psicólogo):**

**Registro das consultas (Psicólogo):** 

**Registro das emoções e calendário (Paciente):** 

### 3.3. Modelagem dos processos

[Processo 1 - Cadastro e Gestão da agenda](processo-1-Agendamento-de-Consultas.md "Detalhamento do Processo 1.")

[Processo 2 - Cadastro e Gestão do paciente](processo-2-nome-do-processo.md "Detalhamento do Processo 2.")

[Processo 3 - Registro das consultas](processo-3-Gestão-do-Paciente-e-Histórico-Clínico.md "Detalhamento do Processo 3.")

[Processo 4 - Registro das emoções e calendário](processo-4-estatisticas.md "Detalhamento do Processo 4.")

## 4. Projeto da solução

_O documento a seguir apresenta o detalhamento do projeto da solução. São apresentadas duas seções que descrevem, respectivamente: modelo relacional e tecnologias._

[Projeto da solução](solution-design.md "Detalhamento do projeto da solução: modelo relacional e tecnologias.")


## 5. Indicadores de desempenho

_O documento a seguir apresenta os indicadores de desempenho dos processos._

[Indicadores de desempenho dos processos](performance-indicators.md)


## 6. Interface do sistema

_A sessão a seguir apresenta a descrição do produto de software desenvolvido._ 

[Documentação da interface do sistema](interface.md)

## 7. Conclusão

_Apresente aqui a conclusão do seu trabalho. Deve ser apresentada aqui uma discussão dos resultados obtidos no trabalho, local em que se verifica as observações pessoais de cada aluno. Essa seção poderá também apresentar sugestões de novas linhas de estudo._

# REFERÊNCIAS

_Como um projeto de software não requer revisão bibliográfica, a inclusão das referências não é obrigatória. No entanto, caso você deseje incluir referências relacionadas às tecnologias, padrões, ou metodologias que serão usadas no seu trabalho, relacione-as de acordo com a ABNT._

_Verifique no link abaixo como devem ser as referências no padrão ABNT:_

http://portal.pucminas.br/imagedb/documento/DOC_DSC_NOME_ARQUI20160217102425.pdf

**[1.1]** - _ELMASRI, Ramez; NAVATHE, Sham. **Sistemas de banco de dados**. 7. ed. São Paulo: Pearson, c2019. E-book. ISBN 9788543025001._

**[1.2]** - _COPPIN, Ben. **Inteligência artificial**. Rio de Janeiro, RJ: LTC, c2010. E-book. ISBN 978-85-216-2936-8._

**[1.3]** - _CORMEN, Thomas H. et al. **Algoritmos: teoria e prática**. Rio de Janeiro, RJ: Elsevier, Campus, c2012. xvi, 926 p. ISBN 9788535236996._

**[1.4]** - _SUTHERLAND, Jeffrey Victor. **Scrum: a arte de fazer o dobro do trabalho na metade do tempo**. 2. ed. rev. São Paulo, SP: Leya, 2016. 236, [4] p. ISBN 9788544104514._

**[1.5]** - _RUSSELL, Stuart J.; NORVIG, Peter. **Inteligência artificial**. Rio de Janeiro: Elsevier, c2013. xxi, 988 p. ISBN 9788535237016._

**[1.6]** - Tenho dificuldade de me expressar, [https://www.doctoralia.com.br/perguntas-respostas/tenho-dificuldade-de-me-expressar-por-isso-nao-consigo-ir-ao-psicologo-e-normal-nao-conseguir-se-c].

**[1.7]** - O paciente faltou à consulta e não avisou, [https://nossospsicologos.zendesk.com/hc/pt-br/articles/115000759614-O-paciente-faltou-%C3%A0-consulta-e-n%C3%A3o-avisou-Devo-informar-isso-%C3%A0-plataforma].


# APÊNDICES


_Atualizar os links e adicionar novos links para que a estrutura do código esteja corretamente documentada._


## Apêndice A - Código fonte

[Código do front-end](../src/front) -- repositório do código do front-end

[Código do back-end](../src/back)  -- repositório do código do back-end


## Apêndice B - Apresentação final


[Slides da apresentação final](presentations/)


[Vídeo da apresentação final](video/)






