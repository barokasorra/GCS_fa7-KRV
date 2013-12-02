GCS_FA7-KRV
=================
Plano de Gerenciamento de Configuração
======================================
Versão 1.0
------------------

_[Observação: O template a seguir é fornecido para uso com o Rational Unified Process (RUP).  O texto exibido entre colchetes e em itálico foi incluído para orientar o autor e deve ser excluído antes da publicação do documento._

_Este documento utiliza a formatação da linguagem [Markdown] (http://daringfireball.net/projects/markdown/). Você pode encontrar um guia de referência rápido [aqui] (https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).]_

Histórico de Versões
--------------------

|Data                |Versão       |Descrição               |Autor          |Email          |
|--------------------|-------------|------------------------|---------------|---------------|
| 26/11/2013 | 1.0 | Versão inicial | Kalebe Barros| barokasorra@gmail.com |
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
_[Descreva quem será o responsável pela execução das diversas atividades de Gerenciamento de Configuração (CM) descritas no Processo de CM.]_

2.2 Ferramentas, Ambiente e Infra-estrutura
-------------------------------------------
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

Todos os artefatos gerados, com exceção de código fonte, neste projeto terão a seguinte nomenclatura:

<b>KRV\_&lt;ID\_ARTEFATO&gt;\_&lt;TEXTO\_LIVRE&gt;.&lt;EXT&gt;</b>

Onde:

| Identificador        | Descrição                                         |
|----------------------|---------------------------------------------------|
| &lt;ID\_ARTEFATO&gt; | É a identificação do artefato, conforme tabela 1. |
| &lt;TEXTO\_LIVRE&gt; | Texto livre que identifique unicamente o arquivo. |
| &lt;EXT&gt;          | A extensão do arquivo. Ex.: doc, xls, java, etc.  |

Faz-se necessário que as letras que compoẽm o identificador esteja em caixa alta, onde estão listados na tabela 1, logo abaixo.

| Identificador        | Artefato                                          |
|----------------------|---------------------------------------------------|
| ARCH                 | Documento de arquitetura.                         |
| ARE                  | Ata de reuniões.                                  |
| CMD                  | Modelo, ou diagrama, de classes.                  |
| MER                  | Modelo de entidade-relacionamento.                |
| PTS                  | Plano de teste de software.                       |
| REQ                  | Documento de requisito.                           |
| RPT                  | Relatório de status, métricas, bugs, etc.         |
| TAP                  | Termo de abertura do projeto.                     |
| TST                  | Caso de teste.                                    |
| UC                   | Caso de uso.                                      |

### 3.1.2 Itens de Configuração

| Item (ou Tipo de Item)     | Responsável na equipe | Inclusão em Baseline |
|----------------------------|-----------------------|----------------------|
| Documento de requisitos    | Roberto Rodrigues     |_&lt;momento a partir do qual o conjunto de artefatos será incluído em baseline&gt;_|
| Código fonte               | Virgulino Ximenes     |_&lt;momento a partir do qual o conjunto de artefatos será incluído em baseline&gt;_|
| Plano de testes            | Kallel Barros         |_&lt;momento a partir do qual o conjunto de artefatos será incluído em baseline&gt;_|
| Manuais de instalação e uso| Ricardo Barros        |_&lt;momento a partir do qual o conjunto de artefatos será incluído em baseline&gt;_|
|Descrição do banco de dados | Virgilio  Rodrigues   |_&lt;momento a partir do qual o conjunto de artefatos será incluído em baseline&gt;_|
| Programa Executável        | Kalebe Ximenes        |_&lt;momento a partir do qual o conjunto de artefatos será incluído em baseline&gt;_|
| Cronograma                 | Ricardo Rodrigues     |_&lt;momento a partir do qual o conjunto de artefatos será incluído em baseline&gt;_|
| Relatório de testes        | Virgilio Ximenes      |_&lt;momento a partir do qual o conjunto de artefatos será incluído em baseline&gt;_|
|Plano de projeto do software| Kalebe Barros         |_&lt;momento a partir do qual o conjunto de artefatos será incluído em baseline&gt;_|
|Termo de abertura do projeto| Joaquim Oliveira      |_&lt;momento a partir do qual o conjunto de artefatos será incluído em baseline&gt;_|

### 3.1.3 Baselines do Projeto

As baselines serão criadas quando um dos seguintes fatos ocorrerem:
- Início do projeto;
- Cliente assinar termo de aceite;
- Fim de ciclo de desenvolvimento;
- Entrega de _release_ para o cliente;
- Alteração de item de configuração;
- Entrega do produto final do projeto.    

Para que se dê a criação de uma baseline, é necessário que o gerente de configuração autorize, haja vista que o mesmo estará envolvido em todas as etapas do projeto, sendo este responsável por preparar o ambiente em que os artefatos serão versionados.

A baseline, quando criada, conterá:
- Codigo fonte
- Documento de requisitos
- TAP
- Casos de teste
- Casos de uso

### 3.1.4 Estrutura do Repositório de Versões

| Diretório | Conteudo                                                       |
|-----------|----------------------------------------------------------------|
| code      | Diretório relacionado ao código fonte do produto.              |
| /src      | Código fonte.                                                  |
| /lib      | Bibliotecas, framework e componentes utilizados.               |
| /docs     | Documentação do código fonte.                                  |
| /build    | Rotinas a serem utilizadas para geração do executável.         |
| /database | Descrição do banco de dados, triggers e procedures necessárias.|
| manage    | Diretório relacionado ao gerenciamento do projeto.             |
| /require  | Documentos relacionados aos requisitos.                        |
| /test     | Documentos de procedimentos de testes, planos de teste, etc.   |
| /reunioes | Atas de reunioes.                                              |
| /report   | Relatórios de status, métricas, bugs.                          |
| /project  | Especificação do processo do projeto.                          |

3.2 Controle de Configuração e Mudança
--------------------------------------

### 3.2.1 Processamento e Aprovação de Solicitações de Mudança
A solicitação de mudança (CR) deve ser deve ser registrada no JIRA, disponível [no site do projeto](http://www.google.com.br). Algumas informações são necessárias para a devida criação do solicitação.

| Campo | Tipo        | Descrição                                            |
|-------|-------------|------------------------------------------------------|
| Tipo  | Obrigatório | Indica se é um erro, uma sugestão, melhoria, nova atividade ou tarefa (não requer mudança). |
| Prioridade | Obrigatório | Quanto menor o número, mais alta é a prioridade. |
| Responsável | Opcional | Profissional da equipe responsável por atender a demanda. |
| Palavras chave | Opcional | Palavras chaves para encontrar o problema. É utilizado na manutenção da base de conhecimento. |
| URL | Opcional | Link para um site externo que auxilie na resolução da solicitação. |
| Sumário | Obrigatório | Breve descrição da solicitação. |
| Descrição | Obrigatório | Descrição detalhada da solicitação. |
| Imagens | Opcional | Imagens que auxiliem na resolução da solicitação. |

Estas informações são necessárias a criação da CR. Abaixo é apresentado como é o ciclo de vida da CR.

| Estado | Descrição   | Atividades |
|--------|-------------|---------------------------------|
| Novo   | A CR é criada | O criador responsável informou os dados. A CR será analisada internamente. |
| Analisado | A CR é analisada por consultores internos. | O consultor analisou e, caso esteja com dados inválidos, a CR é cancelada, caso os dados estejam válidos, o criador responsável deverá aprovar a análise, a estimativa de horas e o custo, ou não. |
| Aprovado | O criador aprova a análise. | O criador entendeu o que será afetado pelas alterações, qual a estimativa de tempo/custo para realizar o que foi solicitado. O consultor é notificado e a equipe poderá começar a trabalhar na CR. |
| Iniciada | A CR é atribuída a um responsável pela implementação. | O consultor indica quem será responsável por implementar a CR, o criador é notificado que a CR começou a ser implementada. |
| Implementada | A CR foi resolvida. | A documentação foi atualizada, foram criados testes para a CR, é disponibilizada a versão para a equipe de testes. |
| Validada | As modificações foram aceitas pela validação. | A CR foi validada e homologada pela equipe de testes, a _release_ é disponibilizada, juntamente com a documentação. |
| Fechada | A CR está completa. | Nenhuma. |
| Re-aberta | A CR foi julgada incompleta pelo criador. | Igual ao estado _Novo_ |

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
