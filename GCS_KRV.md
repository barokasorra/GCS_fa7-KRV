GCS_FA7-KRV
=================
Plano de Gerenciamento de Configuração
======================================
Versão 1.1
------------------



_[Observação: O template a seguir é fornecido para uso com o Rational Unified Process (RUP).  O texto exibido entre colchetes e em itálico foi incluído para orientar o autor e deve ser excluído antes da publicação do documento._

_Este documento utiliza a formatação da linguagem [Markdown] (http://daringfireball.net/projects/markdown/). Você pode encontrar um guia de referência rápido [aqui] (https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).]_

Histórico de Versões
--------------------

|Data                |Versão       |Descrição               |Autor        |
|:------------------:|:-----------:|:----------------------:|:-----------:|
| 26/11/2013         | 1.0 | Versão inicial | Kalebe Barros|
| 28/11/2013         | 1.1 | GCS | Kalebe Barros|
|_&lt;dd/mm/aaaa&gt;_|_&lt;1.1&gt;_|_&lt;Outra versão&gt;_  |_&lt;autor&gt;_|_&lt;autor&gt;_|



1. Introdução
==============

_[A introdução do Plano de Gerenciamento de Configuração  oferece uma visão geral de todo o documento. 
Ela inclui a finalidade, o escopo, as definições, os acrônimos, as abreviações, as referências e uma visão geral deste
Plano de Gerenciamento de Configuração.]_

1.1 Finalidade
---------------
A finalidade deste documento é criar um padrão a ser seguido por todos os membros da equipe com o intuito de garantir o maior controle do produto no decorrer do projeto. 
Para que isso aconteça serão detalhados os recursos necessários (equipes, ferramentas e computadores), as responsabilidades atribuídas e o cronograma de atividades.


1.2 Escopo
----------
_[Uma breve descrição do escopo deste Plano de Gerenciamento de Configuração; o modelo ao qual ele está associado e tudo o que é afetado ou influenciado por este documento.]_

1.3 Definições, Acrônimos e Abreviações
---------------------------------------
|TERMO               |SIGNIFICADO       |
|--------------------|-------------|
| Baseline | Conjunto de itens de configuração que conseguiram um estado comprovado de estabilidade. |
|_&lt;TERMOS;_|_&lt;Significados&gt;_|
_[Esta subseção apresenta as definições de todos os termos, acrônimos e abreviações necessários para a correta interpretação do Plano de Gerenciamento de Configuração.  Essas informações podem ser fornecidas mediante referência ao Glossário do projeto.]_

1.4 Referências
---------------
_[Esta subseção apresenta uma lista completa de todos os documentos mencionados no Plano de Gerenciamento de Configuração. Identifique os documentos por título, número de relatório (se aplicável), data e organização responsável pela publicação. Especifique as fontes a partir das quais as referências podem ser obtidas. Essas informações podem ser fornecidas por um anexo ou outro documento.]_

1.5 Visão Geral
---------------
_[Esta subseção descreve o conteúdo restante do Plano de Gerenciamento de Configuração e explica como o documento está organizado.]_



2. Gerenciamento de Configuração de Software
============================================

2.1 Organização, Responsabilidades e Interfaces
------------------------------------------------
|PAPÉIS        |EQUIPE    |RESPOSABILIDADE       |
|:------------:|:-----------:|:------------:|
|Gerente de Configuração| Virgilio Ximenes |Estabelecer Políticas de GC,    Escrever Plano de GC,  Configurar Ambiente de GC,  Criar Espaços de Trabalho de Integração,  Criar Baselines,  Promover Baselines|
|CCM| Kalebe Barros  Ricardo César |Estabelecer Processo de Controle de Mudanças,  Revisar Solicitação de Mudança|
|Desenvolvedor|Ricardo César  Virgilio Ximenes|Seguir os padrões e procedimentos definidos no Plano de Gerência de Configuração|
**Tabela 01 - Responsavéis e Resposabilidades**

_[Descreva quem será o responsável pela execução das diversas atividades de Gerenciamento de Configuração (CM) descritas no Processo de CM.]_

2.2 Ferramentas, Ambiente e Infra-estrutura
-------------------------------------------
##### 2.2.1	As ferramentas a serem utilizadas para a gerência de configuração
|Ferramenta	     |Tipo	    |Descrição	    |Versão    |
|----------------|----------|---------------|----------|
|GIT	         |Controle de Versão|Sistema de controle de versão. Localizado através do endereço: http://git-scm.com/|	1.4.6|
|GitHub	         |Repositório	OnLine| Projeto on-line de hospedagem com Git. Inclui navegador de código-fonte, a edição in-line, wikis.Localizado através do Endereço: “https://github.com/” ||
|MdCharm|Editor MarkDown|É um editor de wiki. Atualmente ele suporta MarkDown e MultiMarkDown.Localizado através do Endereço: “http://www.mdcharm.com/”|1.1.6|

##### 2.2.2	Configuração do software – Ferramentas do ambiente de desenvolvimento
|Tipo   |Ferramenta	    |Versão    |
|----------------|----------|---------------|
|Sistema Operacional (Desenvolvimento)|	Windows XP Professional	SP2|
|Cronograma	|Microsoft Office Project|2013|
|Planilha|Microsoft Office Excel|2013|
|Editor de Texto|Microsoft Office Word|2013
|Controle de Versão|GIT|| 
|Plataforma de Desenvolvimento|Ferramenta: Eclipse   Linguagem: JAVA |	|
|Banco de Dados|Mysql	5.0||
|Maquina virtual|	VMWare|	1.0.4|
|Comunicação|Telefone	/ Skype / Hangout|

##### 2.2.3 Estrutura de Ambiente

_[Descreva o ambiente de computação e as ferramentas de software a serem utilizadas para desempenhar as funções de CM em todo o ciclo de vida do projeto ou produto._
_Descreva as ferramentas e os procedimentos necessários utilizados para o controle de versão dos itens de configuração gerados no ciclo de vida do projeto ou produto._
_As questões envolvidas na configuração do ambiente de CM incluem:_
* _tamanho previsto dos dados do produto_
* _distribuição da equipe do produto_
* _localização física dos servidores e clientes]_
 


3. O Programa de Gerenciamento de Configuração
==============================================

3.1 Identificação da Configuração
---------------------------------
### 3.1.1 Métodos de Identificação
----------------------------------
_[Descreva como os artefatos do projeto ou produto devem ser nomeados, marcados e numerados. O esquema de identificação deve abranger o hardware, o software do sistema, os produtos de terceiros (COTS) e todos os artefatos de desenvolvimento de aplicativos listados na estrutura de diretórios do produto; por exemplo, planos, modelos, componentes, software de teste, resultados e dados, executáveis e assim por diante.]_

### 3.1.2 Itens de Configuração
_[Relacionar os artefatos ou grupos de artefatos, separando por tipo, modulo ou subsistema, responsável ou momento em que deverão ser incluídos em baselines._
* _“Inclusão em Baseline” em branco significa que o grupo de artefatos não participará de baseline. Pode ser expresso como uma data ou identificador de uma baseline, fase ou ponto de controle_
* _“Responsável”: indicar nominalmente, sempre que possível]_

| Item (ou Tipo de Item)                 | Responsável na equipe	     | Inclusão em Baseline |
|----------------------------------------|-----------------------------|----------------------|
|_&lt;grupo de itens de configuração&gt;_|_&lt;nome do responsável&gt;_|_&lt;momento a partir do qual o conjunto de artefatos será incluído em baseline&gt;_|


### 3.1.3 Baselines do Projeto

_[As baselines funcionam como um padrão oficial no qual os trabalhos subseqüentes são baseados. Somente mudanças autorizadas podem ser efetuadas nas baselines._
_Descreva em que pontos do ciclo de vida do projeto ou produto as baselines devem ser estabelecidas. As baselines mais comuns devem ser definidas ao final de cada uma das fases de Iniciação, Elaboração, Construção e Transição. Elas também podem ser geradas no final de iterações ocorridas dentro das várias fases ou com freqüência ainda maior._
_Descreva quem autoriza uma baseline e o que ela contém.]_

### 3.1.4 Estrutura do Repositório de Versões
_[Descreva a organização de diretórios do seu repositório e que itens/arquivos devem ser armazenados em cada diretório.]_

3.2 Controle de Configuração e Mudança
--------------------------------------

### 3.2.1 Processamento e Aprovação de Solicitações de Mudança
_[Descreva o processo pelo qual os problemas e as mudanças são submetidos, revisados e dispostos. Inclua como funciona a transição de estados de uma solicitação de mudança]_

### 3.2.2 Comitê de Controle de Mudança (CCB)
_[Descreva a participação e os procedimentos para processar solicitações e aprovações de mudança a serem seguidos pelo CCB. Informe quem são os membros do CCB e suas responsabilidades.]_



4. Padrões e Procedimentos
==========================
_[Descreva os padrões e procedimentos que devem ser seguidos no projeto. Crie subseções se achar necessário, para organizá-los melhor.]_



5. Treinamento e Recursos
=========================
_[Descreva as ferramentas de software, o pessoal e o treinamento necessários para implementar as atividades de CM especificadas.]_



6. Auditorias de Configuração
=============================
_[Descreva o cronograma das auditorias de configuração e o que será verificado. Informe também como serão reportados os problemas encontrados e onde sera feito o acompanhamento dos itens corretivos.]_
