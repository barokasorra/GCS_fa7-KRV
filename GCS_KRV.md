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
| 29/11/2013         | 1.2 | Treinamentos | Kalebe Barros|
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
|:------------:|:-----------:|------------|
|Gerente de Configuração| Virgilio Ximenes |Estabelecer Políticas de GC</br>   Escrever Plano de GC</br>  Configurar Ambiente de GC</br>  Criar Espaços de Trabalho de Integração</br>  Criar Baselines</br>  Promover Baselines|
|CCM| Kalebe Barros  Ricardo César |Estabelecer Processo de Controle de Mudanças</br>  Revisar Solicitação de Mudança|
|Desenvolvedor|Ricardo César</br >Virgilio Ximenes|Seguir os padrões e procedimentos definidos no Plano de Gerência de Configuração|


2.2 Ferramentas, Ambiente e Infra-estrutura
-------------------------------------------
##### 2.2.1	Ferramentas a serem utilizadas para a gerência de configuração


|Ferramenta	     |Tipo	    |Descrição	    |Versão    |
|----------------|----------|---------------|:----------:|
|GIT	         |Controle de Versão|Sistema de controle de versão. </br>Localizado através do endereço: http://git-scm.com/|	1.8.4|
|GitHub	         |Repositório	OnLine| Projeto on-line de hospedagem com Git. Inclui navegador de código-fonte, edição in-line, wikis.</br>Localizado através do Endereço: “https://github.com/” |***|
|MdCharm|Editor MarkDown|É um editor de wiki. Atualmente ele suporta MarkDown e MultiMarkDown.</br>Localizado através do Endereço: “http://www.mdcharm.com/”|1.1.6|


##### 2.2.2	Configuração do software – Ferramentas do ambiente de desenvolvimento


|Tipo   |Ferramenta	    |Versão    |
|----------------|----------|:---------------:|
|Sistema Operacional (Desenvolvimento)|	Windows 7 Ultimate	|SP1|
|Cronograma	|Microsoft Office Project|2013|
|Planilha|Microsoft Office Excel|2013|
|Editor de Texto|Microsoft Office Word|2013
|Controle de Versão|GIT|1.8.4| 
|Plataforma de Desenvolvimento|Ferramenta: Eclipse Standard</br><br>Linguagem: JAVA SE |4.3.1</br><br>7u45	|
|Banco de Dados|Mysql	|6.0|
|Maquina virtual|	VirtualBox |	4.3.2|
|Comunicação|Telefone	/ Skype / Hangout|


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
| Documento de requisitos    | Roberto Rodrigues     | Quando o cliente validar o documento |
| Código fonte               | Virgulino Ximenes     | Quando o cliente homologar a implementação |
| Plano de testes            | Kallel Barros         | Quando o gerente de testes |
| Manuais de instalação e uso | Ricardo Barros        | Quando o gerente suporte validar |
| Descrição do banco de dados | Virgilio Rodrigues   | |
| Programa Executável        | Kalebe Ximenes        | |
| Cronograma                 | Ricardo Rodrigues     | Quando o cliente homologar |
| Relatório de testes        | Virgilio Ximenes      | Após a execução da _build_ |
|Plano de projeto do software| Kalebe Barros         | |
|Termo de abertura do projeto| Joaquim Oliveira      | Após o cliente assinar |

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

O CCB será composto de um gerente de cada time, que são:

* Desenvolvimento: Analisar o impacto da CR;
* Teste: Analisar os testes que necessitarão ser alterados para abranger a CR, avaliando os riscos e como mitigá-los;
* Suporte Técnico: Analisar os manuais que necessitarão ser alterados para abranger a CR;
* Financeiro: Analisar a viabilidade financeira;
* Comercial: Analisar o alinhamento quanto ao negócio;
* Gerência de projetos: Analisar quanto ao escopo do projeto.

A análise irá iniciar com o relatório da análise de impacto realizado pela equipe de desenvolvimento, apresentando no relatório a quantidade de horas necessárias para realizar a alteração. Somente então a equipe de teste irá avaliar o esforço necessário para criar ou alterar os testes, bem como o suporte analisará os manuais que necessitarão de criação ou alteração. Com base nessas informações, o financeiro irá calcular os custos envolvidos. De posse dos custos, o comercial poderá avaliar quanto ao alinhamento da CR com o negócio, atribuindo a priorização da CR, para, finalmente, a gerência de projeto poder analisar o prazo para a entrega, quando a CR integrará o escopo do projeto. Caso a maioria dos membros do CCB aprovem a CR, o formulário deverá ser preenchido.

| ID  | Atividade | Feito? |
|-----|-----------|--------|
|  1. | Obtidas alterações solicitadas e correções de bugs propostas para inclusão na _release_. | |
|  2. | Identificadas implementações, testes, integrações e prazo estimado. | |
|  3. | Avaliadas as funcionalidades, o orçamento, o cronograma, os custos, os riscos. | |
|  4. | Se aprovada, verificados se serão necessários novos componentes ou alterar os existentes, documentos do projeto e outros artefatos dentro da gerência de configuração. | |

4. Padrões e Procedimentos
==========================
_[Descreva os padrões e procedimentos que devem ser seguidos no projeto. Crie subseções se achar necessário, para organizá-los melhor.]_



5. Treinamento e Recursos
=========================

|Treinamento|Objetivo|Público Alvo|
|:---:|---|:---:|
|Repositório|Ensinar como acessar o repositório através do _GIT_,</br> Como dar os comandos principais do repositório,  como incluir, atualizar e excluir itens dentro do repositório, e, </br>Como colocar os arquivos no repositório online _(GitHub)_.|Toda equipe|


6. Auditorias de Configuração
=============================

A auditoria será realizada sempre antes da liberação da _baseline_ para o cliente, sendo responsável por verificar se o que está sendo liberado para o cliente está completo, no que tange as cláusulas contratuais, e correta, atendendo ao requisitos estabelecidos.
A auditoria será responsável por verificar se os componentes estão presentes nas versões especificadas e confirmar a presença de todos os artefatos necessários.
Caso, durante a auditoria, alguma falha seja encontrada devem ser executados os seguintes passos:
<ol>
<li>Identificiação do problema, apresentando a discrepância nos artefatos envolvidos.</li>
<li>Identificar ação corretiva junto aos membros do CCB.</li>
<li>Se for detectado a ausência de algum artefato, deve ser comunicado ao gerente de configuração para incluí-lo no gerenciamento de configuração.</li>
<li>Se um requisito não for atendido plenamente, deve ser postergado para uma <i>baseline</i> futura ou negociar para cancelá-lo.</li>
<li>Se uma CR estiver em aberto, deverá ser analisado qual o melhor encaminhamento, se deverá ser fechada, cancelada ou adiada.</li>
</ol>
