# ➕PSIPLUS

## Autores

- **Nico Jobski Andrade, jobskiandrade@gmail.com**
- **Júlia de Souza Ventura, juliavt403@gmail.com**
- **Rafael Rocha Caldeira Brant, rafaelrbrant07@gmail.com**
- **Ana Luiza de Freitas Rodrigues, analuizafreitas12@yahoo.com.br**
- **Kayke Emanoel de Souza Santos, kaykeeman@gmail.com**
- **Carlos Eduardo Sousa Santos, cadusantos9000@gmail.com**

---

## Professores Orientadores:

- **Michelle Hanne Soares de Andrade**   
- **Danilo de Quadra Maia Filho**  
- **Joana Gabriela Ribeiro de Souza**  

---

## Instituição

📌 _Curso de Engenharia de Software_  
🏛️ _Instituto de Informática e Ciências Exatas – Pontifícia Universidade Católica de Minas Gerais (PUC MINAS)_  
📍 _Belo Horizonte – MG – Brasil_

---

## 📌 Resumo

Esse projeto visa desenvolver uma plataforma online para psicólogos, centralizando todas as funcionalidades essenciais em um só lugar. O sistema permitirá o agendamento de consultas, controle dos pacientes e o registro do estado emocional deles, proporcionando mais organização e eficiência. O objetivo é otimizar a rotina dos profissionais e aprimorar a experiência dos pacientes, eliminando a necessidade de múltiplas ferramentas e garantindo um atendimento mais fluido e integrado.

---


## 1. 📖 Introdução

No mundo digital de hoje, até os consultórios de psicologia precisam se modernizar. Muitos profissionais ainda dependem de métodos manuais ou de sistemas desconexos para agendar, gerenciar consultas e acompanhar o bem-estar dos pacientes. Pensando nisso, surge a proposta de desenvolver uma plataforma integrada que reúne todas essas funcionalidades em um só lugar, tornando o dia a dia dos psicólogos muito mais prático.

### 1.1 Contextualização

Atualmente, é comum que os psicólogos utilizem diversos sistemas separados para realizar suas atividades diárias, como plataformas para preenchimento de cadastros e formulários (Google Forms), ferramentas para agendamento de consultas(Zenklub, Virtude), agendas de gestão virtuais (PsicologiaNET, ClinicaWEB), além de diferentes métodos para anotação e avaliação dos pacientes. Essa fragmentação de processos pode gerar desafios na gestão eficiente das informações e no acompanhamento do progresso dos pacientes.
Diante desse cenário, surge uma oportunidade para integrar e potencializar essas funcionalidades, criando uma solução que unifique esses processos. Além disso, visamos desenvolver novas abordagens para avaliação psicológica, oferecendo recursos como a apresentação de estatísticas e dados detalhados sobre o estado de cada paciente, facilitando a gestão do trabalho do psicólogo e promovendo uma visão mais clara e completa sobre os casos tratados.

### 1.2 Problema

Na psicoterapia, desafios impactam a qualidade do atendimento e a eficiência dos profissionais. A comunicação, a organização das consultas e o acompanhamento do progresso são essenciais, mas limitações estruturais e operacionais dificultam o processo. Os principais problemas são:

❌ **Dificuldade dos pacientes em expressar sentimentos:** 
Muitos indivíduos enfrentam barreiras emocionais e psicológicas ao tentar comunicar seus sentimentos e experiências durante as sessões terapêuticas. Essa dificuldade pode ser resultado de diversos fatores, como traumas, medo de julgamento ou falta de hábito em verbalizar emoções. Como consequência, o psicólogo pode ter acesso limitado a informações essenciais para compreender a fundo a realidade do paciente, o que pode comprometer a eficácia do tratamento. É comum que pacientes sintam dificuldades em se expressar verbalmente, o que é apontado em diversas fontes, como [1.6], onde a dificuldade de comunicação é discutida como um fator importante na terapia.

❌ **Falta de ferramentas para monitoramento contínuo:**
O processo terapêutico não se limita apenas às sessões presenciais. O estado emocional dos pacientes oscila ao longo do tempo, e sem um meio eficiente para registrar e compartilhar essas mudanças com o psicólogo, torna-se mais difícil acompanhar a evolução do paciente de forma estruturada. A ausência de uma ferramenta para esse acompanhamento contínuo pode reduzir a precisão do diagnóstico e a personalização das intervenções terapêuticas.

❌ **Gestão ineficiente de consultas:**
O gerenciamento manual da agenda pode gerar problemas como conflitos de horários, esquecimentos e dificuldades na organização do tempo do profissional. Falhas nos agendamentos podem resultar em ausências e menor aproveitamento das sessões. A falta de lembretes automatizados também pode aumentar o índice de faltas, como discutido em [1.7], que aborda as implicações dessas ausências no processo terapêutico.

❌ **Armazenamento e acesso inadequados a registros clínicos:**
Manter um histórico detalhado e seguro dos atendimentos é essencial para que o psicólogo possa acompanhar a trajetória do paciente e tomar decisões mais assertivas no tratamento. Entretanto, a ausência de um sistema centralizado e seguro pode resultar em perda de informações importantes, dificultando a análise do progresso do paciente e a continuidade do tratamento em longo prazo.

❌ **Comunicação limitada entre sessões:**
A relação entre paciente e psicólogo não deve ser restrita apenas ao momento da consulta. Em muitos casos, os pacientes passam por situações difíceis entre as sessões e não têm um canal adequado para relatar suas emoções ou receber suporte. A falta de uma comunicação estruturada fora das consultas pode prejudicar a continuidade do tratamento e gerar uma sensação de isolamento no paciente.

Esses desafios evidenciam a necessidade de uma solução integrada que otimize a comunicação, o acompanhamento e a gestão no contexto da psicoterapia. Com um sistema estruturado, é possível aprimorar significativamente a experiência dos pacientes e a eficiência do trabalho dos profissionais da área.

### 1.3 Objetivo geral

Desenvolver o PSI+, um sistema de gestão digital para psicólogos e pacientes que centralize as principais funcionalidades necessárias para uma prática clínica eficiente e organizada. A plataforma tem como foco a organização da agenda profissional, oferecendo um sistema de agendamento simples e intuitivo, além de um canal de comunicação seguro entre psicólogos e pacientes. O PSI+ permitirá o registro diário das emoções dos pacientes, facilitando um acompanhamento mais próximo por parte do profissional. O objetivo é criar uma solução acessível, intuitiva e prática, tornando a gestão das consultas mais eficiente e a experiência do usuário mais fluida e livre de complicações.

#### 🎯 1.3.1 Objetivos específicos

1️⃣ **Criação de um sistema de agendamento intuitivo:** 
Desenvolver um sistema de agendamento simples e eficiente, que permita aos psicólogos gerenciar seus horários de maneira prática, com uma interface fácil de usar para agendar e organizar as consultas, evitando conflitos de horários e aumentando a eficiência do processo.

2️⃣ **Estabelecimento de um canal de comunicação eficaz:** 
Implementar um canal de comunicação direto entre psicólogos e pacientes, facilitando a troca de informações importantes entre as sessões, o que permitirá ao paciente relatar seu progresso ou dificuldades emocionais de maneira contínua e ao psicólogo acompanhar esses relatos para intervenções mais precisas.

3️⃣ **Implementação de um módulo de monitoramento emocional:** 
Criar uma ferramenta para o registro e monitoramento contínuo dos sentimentos dos pacientes, permitindo o acompanhamento detalhado das flutuações emocionais ao longo do tempo. Esse módulo ajudará a oferecer uma visão mais clara do progresso do paciente, permitindo um tratamento mais personalizado e adaptado às suas necessidades.

4️⃣ **Proporcionar uma experiência de uso agradável e acessível:**
Garantir que o sistema seja acessível e fácil de navegar, promovendo uma experiência de uso agradável tanto para os psicólogos quanto para os pacientes. A interface será projetada para ser intuitiva, com foco na simplicidade, facilitando a navegação e o uso, independentemente do nível de familiaridade com tecnologia.

5️⃣ **Gestão eficiente das consultas e registros clínicos:** 
Criar um sistema de gestão de consultas que permita o controle preciso dos horários, o registro detalhado do histórico de atendimentos e a organização das sessões de maneira eficiente. Isso contribuirá para uma gestão sem erros, aumentando a produtividade e proporcionando aos psicólogos um acesso rápido e organizado a todos os dados clínicos necessários para o acompanhamento contínuo do paciente.

### 1.4 Justificativas

A gestão de práticas psicológicas enfrenta desafios que impactam tanto os profissionais quanto os pacientes, comprometendo a qualidade do atendimento e a continuidade do tratamento. Entre os principais problemas enfrentados estão:

📌 Desorganização da agenda – A falta de um sistema eficiente pode resultar em atrasos, ausências e dificuldades na continuidade do tratamento, prejudicando o acompanhamento do paciente.
📌 Dificuldade no acompanhamento das emoções dos pacientes – Muitos pacientes enfrentam barreiras para expressar seus sentimentos durante as sessões, o que pode comprometer a eficácia da terapia.
📌 Comunicação limitada entre sessões – A ausência de um canal estruturado para que os pacientes relatem sua evolução dificulta o trabalho do psicólogo e pode afetar o desenvolvimento do tratamento.
📌 Falta de ferramentas para auxiliar na expressão emocional dos pacientes – Nem todos os pacientes conseguem verbalizar suas emoções com facilidade, o que pode atrasar o progresso terapêutico. 

🔹 Solução proposta: Psi+

O projeto Psi+ surge como uma inovação na área da psicologia, oferecendo um sistema digital de gestão que visa tornar o atendimento mais organizado e eficiente.

✅ Calendário de emoções – Um recurso que permite aos pacientes registrarem seus sentimentos de forma contínua e acessível. Isso possibilita ao psicólogo uma visão mais ampla do estado emocional do paciente, tornando as sessões mais produtivas.
✅ Ferramenta automatizada de notificações – Envio de lembretes automáticos via e-mail e mensagens um dia antes da consulta para confirmação ou cancelamento, garantindo um melhor aproveitamento da agenda.
✅ Melhoria na comunicação entre paciente e psicólogo – A integração de um espaço digital para troca de informações permite que o profissional acompanhe a evolução do paciente entre as sessões, otimizando o tratamento.
✅ Integração do agendamento, comunicação e acompanhamento emocional – Um sistema unificado que simplifica a rotina do psicólogo, garantindo mais organização e eficiência no atendimento.

Este trabalho se justifica pela crescente demanda por soluções tecnológicas na área da saúde mental, especialmente na psicologia, e pela necessidade de um sistema que otimize o gerenciamento tanto para o profissional quanto para o paciente. A proposta de um sistema digital de gestão possibilita a integração do agendamento, da comunicação e do acompanhamento emocional em uma única plataforma, simplificando o dia a dia do psicólogo e promovendo um atendimento mais organizado e eficiente. Além disso, o uso da tecnologia como aliada no processo terapêutico torna as informações mais acessíveis e gerenciáveis, contribuindo para uma experiência mais completa e satisfatória para ambas as partes.

## 🏥 2. Participantes do processo

### 2.1. ⚕️ Psicólogo 

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

### 2.2. 💼 Paciente

- Agendar e remarcar consultas de forma prática e rápida
- Registrar emoções e eventos diários para compartilhar com o psicólogo
- Ter acesso ao histórico das próprias emoções e identificar padrões emocionais
- Comunicar-se de maneira segura e pontual com o psicólogo entre as sessões
- Sentir-se mais ativo no próprio processo terapêutico através do acompanhamento digital
- Garantir que suas informações e registros estejam protegidos e acessíveis quando necessário

## 🔄 3. Modelagem do processo de negócio

### 3.1. Análise da situação atual

Muitos psicólogos enfrentam desafios na gestão de suas práticas clínicas devido à falta de sistemas integrados para agendamento, acompanhamento emocional e comunicação entre sessões. A dependência de métodos manuais ou sistemas desconexos gera agendamentos confusos, dificuldades no monitoramento contínuo dos pacientes e limitações na comunicação, prejudicando a qualidade do atendimento e a eficiência terapêutica.

1️⃣ **Cadastro e Gestão da agenda (Psicólogo):** 

2️⃣ **Cadastro e Gestão do paciente (Psicólogo):**

3️⃣ **Registro das consultas (Psicólogo):** 

4️⃣ **Registro das emoções e calendário (Paciente):** 

### 3.2. Descrição geral da proposta de solução

O PSI+ é uma plataforma online que centraliza funcionalidades essenciais para a prática psicológica, incluindo agendamento intuitivo, monitoramento contínuo das emoções dos pacientes e comunicação segura entre psicólogos e pacientes. A plataforma também oferece recursos para gestão eficiente das consultas, com controle de horários, histórico e organização das sessões. O objetivo é otimizar a rotina dos profissionais e melhorar a experiência dos pacientes, promovendo um atendimento mais organizado e eficiente.

1️⃣ **Cadastro e Gestão da agenda (Psicólogo):** 

2️⃣ **Cadastro e Gestão do paciente (Psicólogo):**

3️⃣ **Registro das consultas (Psicólogo):** 

4️⃣ **Registro das emoções e calendário (Paciente):** 

### 3.3. Modelagem dos processos

📌 [Processo 1 - Cadastro e Gestão da agenda](processo-1-Cadastro-e-Gestao-da-agenda.md "Detalhamento do Processo 1.")  
📌 [Processo 2 - Cadastro e Gestão do paciente](processo-2-Cadastro-e-Gestao-do-paciente.md "Detalhamento do Processo 2.")  
📌 [Processo 3 - Registro das consultas](processo-3-Registro-das-consultas.md "Detalhamento do Processo 3.")  
📌 [Processo 4 - Registro das emoções e calendário](processo-4-Registro-das-emocoes-e-calendario.md "Detalhamento do Processo 4.")  

## 💡 4. Projeto da solução

_O documento a seguir apresenta o detalhamento do projeto da solução. São apresentadas duas seções que descrevem, respectivamente: modelo relacional e tecnologias._

[Projeto da solução](solution-design.md "Detalhamento do projeto da solução: modelo relacional e tecnologias.")


## 📊 5. Indicadores de desempenho

_O documento a seguir apresenta os indicadores de desempenho dos processos._

[Indicadores de desempenho dos processos](performance-indicators.md)


## 🖥️ 6. Interface do sistema

_A sessão a seguir apresenta a descrição do produto de software desenvolvido._ 

[Documentação da interface do sistema](interface.md)

## 🏁 7. Conclusão

_Apresente aqui a conclusão do seu trabalho. Deve ser apresentada aqui uma discussão dos resultados obtidos no trabalho, local em que se verifica as observações pessoais de cada aluno. Essa seção poderá também apresentar sugestões de novas linhas de estudo._

# 📚 REFERÊNCIAS

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






