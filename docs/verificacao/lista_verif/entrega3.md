# Lista de Verificação - Entrega 3

## Introdução

O artefato apresenta o planejamento da verificação dos artefatos desenvolvidos pelo grupo 4 e grupo 5 durante a Etapa 3 (Modelagem de Requisitos).

## Objetivos

O objetivo deste documento é registrar a lista de verificação da 3ª etapa do Grupo 4, que será utilizada para verificar artefatos do próprio grupo e do Grupo 5.

## Metodologia

Através de reuniões, o grupo decidiu adotar a metodologia de verificação por inspeção desenvolvida por Fagan (Michael E. Fegan) em 1976. Dessa maneira, cada integrante participa na entrega do projeto nos prazos planejados. Cada artefato varificado gera um relatório anexado junto aos demais artefatos daquela entrega. Para responder às perguntas apresentadas nas listas de verificação o avaliador usará as opções **Sim**, **Não**, **Incompleto** ou **Não se aplica**. O avaliador tambem poderá escrever observações para cada item, se achar necessário.

## Lista de Verificação


<center> 

**Tabela 1** – Casos de Uso

| ID  | Descrição | Fonte  | Autor |
| :-: | :-------- | :----- | :---: |
| 01  | O diagrama representa o sistema, que é o software modelado, como um retângulo intitulado pelo nome do sistema?  | <a id="REF1" href="#anchor_1">Vídeo 1</a>, a partir de 01:46 | [João Pedro](https://github.com/JoosPerro) |
| 02  | O diagrama representa <a id="TERM1" href="#term_anchor_1">atores</a> como bonecos-palito posicionados fora do sistema?  | <a id="REF1" href="#anchor_1">Vídeo 1</a>, a partir de 02:10 | [João Pedro](https://github.com/JoosPerro) |
| 03  | Cada ator é intitulado como um tipo ou categoria (como cliente ou banco), ao invés de uma entidade específica (como João ou Banco do Brasil)?  | <a id="REF1" href="#anchor_1">Vídeo 1</a>, a partir de 02:53 | [João Pedro](https://github.com/JoosPerro) |
| 04  | Os atores que iniciam a utilização do sistema (chamados primários) estão posicionados à esquerda do sistema, enquanto os atores que reagem (chamados secundários) estão posicionados à direita?  | <a id="REF1" href="#anchor_1">Vídeo 1</a>, a partir de 03:14 | [João Pedro](https://github.com/JoosPerro) |
| 05  | Os <a id="TERM2" href="#term_anchor_2">casos de uso</a> são representados por uma forma oval, posicionada dentro do sistema?  | <a id="REF1" href="#anchor_1">Vídeo 1</a>, a partir de 04:09 | [João Pedro](https://github.com/JoosPerro) |
| 06  | Cada caso de uso é intitulado com uma frase que começa com um verbo?  | <a id="REF1" href="#anchor_1">Vídeo 1</a>, a partir de 04:50 | [João Pedro](https://github.com/JoosPerro) |
| 07  | Os <a id="TERM3" href="#term_anchor_3">relacionamentos</a> entre ator e ator, entre caso de uso e caso de uso, e entre ator e caso de uso são denotados por algum estilo de linha? | <a id="REF1" href="#anchor_1">Vídeo 1</a>, a partir de 05:41 | [João Pedro](https://github.com/JoosPerro) |
| 08  | Cada caso de uso está relacionado com pelo menos um ator ou outro caso de uso? | <a id="REF1" href="#anchor_1">Vídeo 1</a>, a partir de 05:41 | [João Pedro](https://github.com/JoosPerro) |
| 09  | Os <a id="TERM3" href="#term_anchor_3">relacionamentos associativos</a> são representados como linhas sólidas? | <a id="REF1" href="#anchor_1">Vídeo 1</a>, a partir de 05:17 | [João Pedro](https://github.com/JoosPerro) |
| 10  | Cada ator do diagrama está ligado a pelo menos um caso de uso através um relacionamento associativo?  | <a id="REF1" href="#anchor_1">Vídeo 1</a>, a partir de 05:17 | [João Pedro](https://github.com/JoosPerro) |
| 11  | As flechas tracejadas que representam <a id="TERM3" href="#term_anchor_3">inclusão e extensão</a> de casos de uso são diferenciadas pelos títulos “<<incluir\>\>” e “<<estender\>\>”, respectivamente?  | <a id="REF1" href="#anchor_1">Vídeo 1</a>, a partir de 08:30 e 09:26 | [João Pedro](https://github.com/JoosPerro) |
| 12  | Estão anotadas, junto às extensões, as observações que descrevem as condições para que elas ocorram?  | <a id="REF1" href="#anchor_1">Vídeo 1</a>, a partir de 12:08 | [João Pedro](https://github.com/JoosPerro) |
| 13  | Cada <a id="TERM3" href="#term_anchor_3">generalização</a> está representada com setas sólidas que apontam para caso de uso (ou ator) geral? | <a id="REF1" href="#anchor_1">Vídeo 1</a>, a partir de 11:10 | [João Pedro](https://github.com/JoosPerro) |
| 14  | Casos de uso com <a id="TERM3" href="#term_anchor_3">pontos de extensão</a> são representados como ovais divididas ao meio (um lado com o título, o outro com os pontos de extensão)?  | <a id="REF1" href="#anchor_1">Vídeo 1</a>, a partir de 11:41 | [João Pedro](https://github.com/JoosPerro) |
| 15  | O <a id="TERM3" href="#term_anchor_3">fluxo básico</a> é denotado quando múltiplos fluxos são possíveis?  | <a id="REF2" href="#anchor_2">Caso de Uso ─ Fluxo Alternativo</a> | [João Pedro](https://github.com/JoosPerro) |

</center>

> - <a id="term_anchor_1" href="#TERM1">**Ator**</a>: são entidades externas que interagem com o sistema modelado. Podem ser outros sistemas, pessoas, organizações, etc.
> - <a id="term_anchor_2" href="#TERM2">**Caso de Uso**</a>: são tarefas realizadas por atores, cuja execução deve ser apoiada por funcionalidades contidas no sistema
> - <a id="term_anchor_3" href="#TERM3">**Relacionamento**</a>: são as interações que um elemento do diagrama possui com outros elementos. Os tipos de relacionamentos são:
    - **Associação**: é uma interação entre um ator e uma tarefa que é realizada por ele
    - **Inclusão**: indica dependência entre casos de uso. Sempre que o *caso de uso base* é executado, o *caso de uso incluso* é executado como parte dele
    - **Extensão**: indica um *caso de uso base* que *pode* implicar na execução de outro caso de uso, chamado *estendido*, se cumpridas certas condições. **Pontos de extensão** podem ser informados para o caso de uso base quando ele possuir múltiplos casos de uso estendidos, a fim de especificar os caminhos alternativos
    - **Generalização**: estabelece um caso de teste geral, ou primário, e caso(s) de teste específico(s), ou secundário(s), que herdam todas as características do caso base, e ainda podem ter outras características distintas
> - <a id="term_anchor_4" href="#TERM4">**Fluxo**</a>: é um caminho tomado pelo ator em um sistema, passando por casos de uso conectados por relacionamentos. Existem três tipos básicos de fluxo:
    - O **fluxo básico** é o caminho esperado mais comum de ser tomado, geralmente composto por relacionamentos de inclusão.
    - Um **fluxo alternativo** é um fluxo esperado diferente do fluxo básico, e geralmente são denotados por relacionamentos de extensão.
    - Um **fluxo de exceção** é um fluxo que indica um erro ou um estado indesejado/inesperado, mas que foi previsto por ser possível.

<center>

**Tabela 2** ─ Especificação Suplementar

| ID  | Descrição | Fonte | Autor |
| :-: | :-------- | :---- | :---: |
| 16  | A especificação apresenta os Requisitos Não-Funcionais no modelo FURPS (Funcionalidade, Usabilidade, Confiabilidade (Reliability), Desempenho (Performance) e Suportabilidade)? | <a id="REF3" href="#anchor_3">Modelo de Especificação Suplementar</a> | [João Pedro](https://github.com/JoosPerro) |
| 17 | É especificado o efeito das entradas na saída/resultado do caso de uso? | <a id="REF4" href="#anchor_4">Lista de Verificação Suplementar</a> | [João Pedro](https://github.com/JoosPerro) |
| 18 | São especificadas respostas para situações anormais, como recuperação de erros? | <a id="REF4" href="#anchor_4">Lista de Verificação Suplementar</a> | [João Pedro](https://github.com/JoosPerro) |
| 19 | A especificação apresenta as <a id="TERM5" href="#term_anchor_5">interfaces externas</a> do caso de uso? | <a id="REF4" href="#anchor_4">Lista de Verificação Suplementar</a> | [João Pedro](https://github.com/JoosPerro) |
| 20 | A especificação apresenta mantém rastreabilidade para requisitos derivados de padrões ou normas? | <a id="REF4" href="#anchor_4">Lista de Verificação Suplementar</a> | [João Pedro](https://github.com/JoosPerro) |
| 21 | Foram considerados velocidade, disponibilidade, tempo de resposta e tempo de recuperação das funcionalidades? | <a id="REF4" href="#anchor_4">Lista de Verificação Suplementar</a> | [João Pedro](https://github.com/JoosPerro) |

</center>

> - <a id="term_anchor_5" href="#TERM5">**Interface Externa**</a>: É a especificação de como um software interage com agentes externos, como usuários, hardware e outros softwares

<center>

**Tabela 3** ─ Cenários

| ID  | Descrição | Fonte | Autor |
| :-: | :-------- | :---- | :---: |
| 22 | O cenário descreve uma situação concreta de uso do sistema? | <a id="REF5" href="#anchor_5">Livro de IHC e UX</a> | [João Pedro](https://github.com/JoosPerro) |
| 23 | O cenário possui título, descrição e referência à <a id="TERM6" href="#term_anchor_6">cenários alternativos</a>? | <a id="REF6" href="#anchor_6">Livro de IHC e UX</a> | [João Pedro](https://github.com/JoosPerro) |
| 24 | O cenário descreve o ambiente ou contexto em que ele se passa? | <a id="REF6" href="#anchor_6">Livro de IHC e UX</a> | [João Pedro](https://github.com/JoosPerro) |
| 25 | O cenário descreve o(s) ator(es) envolvidos e seus <a id="TERM7" href="#term_anchor_7">objetivos</a>? | <a id="REF6" href="#anchor_6">Livro de IHC e UX</a> | [João Pedro](https://github.com/JoosPerro) |
| 26 | O cenário descreve o <a id="TERM8" href="#term_anchor_8">planejamento</a> de cada ator? | <a id="REF6" href="#anchor_6">Livro de IHC e UX</a> | [João Pedro](https://github.com/JoosPerro) |
| 27 | O cenário descreve a <a id="TERM9" href="#term_anchor_9">avaliação</a> do ator às situações experienciadas? | <a id="REF6" href="#anchor_6">Livro de IHC e UX</a> | [João Pedro](https://github.com/JoosPerro) |
| 28 | O cenário descerve um dos possíveis fluxos de um caso de uso? |  <a id="REF7" href="#anchor_7">Livro de IHC e UX</a> | [João Pedro](https://github.com/JoosPerro) |

</center>

> - <a id="term_anchor_6" href="#TERM6">**Cenário Alternativo**</a>: um cenário alternativo narra uma maneira diferente de alcançar o mesmo objetivo que outro cenário
> - <a id="term_anchor_7" href="#TERM7">**Objetivo**</a>: é o efeito desejado, é o que motiva o usuário a tomar uma atitude (que pode não se limitar à interação com o sistema em questão)
> - <a id="term_anchor_8" href="#TERM8">**Planejamento**</a>: é a atividade mental do ator para determinar a sequência ações que cumprem seu objetivo
> - <a id="term_anchor_9" href="#TERM9">**Avaliação**</a>: é a atividade mental do ator para interpretar a situação

<center>

**Tabela 4** ─ Léxico

| ID  | Descrição | Fonte | Autor |
| :-: | :-------- | :---- | :---: |
| 29 | O léxico a apresenta a <a id="TERM10" href="#term_anchor_10">noção</a> de cada símbolo? | <a id="REFBIB2" href="#anchor_refbib2">Léxico Ampliado da Linguagem (resumo)</a> | [João Pedro](https://github.com/JoosPerro) |
| 30 | O léxico apresenta o <a id="TERM11" href="#term_anchor_11">impacto</a> de cada símbolo? | <a id="REFBIB2" href="#anchor_refbib2">Léxico Ampliado da Linguagem (resumo)</a> | [João Pedro](https://github.com/JoosPerro) |
| 31 | O léxico indica quais símbolos são sinônimos? | <a id="REFBIB2" href="#anchor_refbib2">Léxico Ampliado da Linguagem (resumo)</a> | [João Pedro](https://github.com/JoosPerro) |
| 32 | Cada símbolo é caracterizado por um, e apenas um, dos seguintes tipos: sujeito, verbo, objeto ou estado? | <a id="REFBIB2" href="#anchor_refbib2">Léxico Ampliado da Linguagem (resumo)</a> | [João Pedro](https://github.com/JoosPerro) |

<a id="term_anchor_10" href="#TERM10">**Noção**</a>: a noção, também chamada *denotação*, é a descrição do significado da expressão/símbolo
<a id="term_anchor_11" href="#TERM11">**Impacto**</a>: o impacto, também chamado *conotação*, é a descrição das implicações/efeitos do seu uso na aplicação. Deve-se indicar os efeitos de um símbolo juntamente com os efeito que afetam/causam esse símbolo.

</center>  

# Evidências

<center>

<a id="anchor_1" href="#REF1">**Vídeo 1** ─ Diagrama de Caso de Uso </a><br>

<iframe width="560" height="315" src="https://www.youtube.com/embed/ab6eDdwS3rA?si=8vzvkAbjoGo7eEGu" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; web-share" allowfullscreen></iframe>

Fonte: [Lucid Software Português](https://www.youtube.com/@lucid_software_portugues)

---

<a id="anchor_2" href="#REF2">**Imagem 2** ─ Fluxo Alternativo de Caso de Uso</a><br>

![Fluxo Alternativo](../referencias/entr3-fluxo-altern.png)

Fonte: [Até o Momento](https://www.ateomomento.com.br/caso-de-uso-fluxo-alternativo/)

---

<a id="anchor_3" href="#REF3">**Imagem 3** ─ Modelo FURPS na Especificação Suplementar </a><br>

![FURPS](../referencias/entr3-furps.png)

Fonte: [MCTIC](https://pdp.mctic.gov.br/MCTI-PDP/guidances/examples/Especificacao%20Suplementar_4C68A4F4.html)

---

<a id="anchor_4" href="#REF4">**Imagem 4** ─ Lista de Verificação de Especificação Suplementar</a><br>

![a](../referencias/entr3-lista-verif-esp-supl.png)

Fonte: [Centro de Informática UFPE](https://www.cin.ufpe.br/~gta/rup-vc/core.base_rup/guidances/checklists/supplementary_specifications_13D7A7B2.html)

---

<a id="anchor_5" href="#REF5">**Imagem 5** ─ O que é um Cenário</a><br>

![a](../referencias/entr3-cenarios1.png)

Fonte: <a id="REFBIB1" href="#anchor_refbib1">Interação Humano-Computador e Experiência de Usuário, p. 172</a>

---

<a id="anchor_6" href="#REF6">**Imagem 6** ─ Elementos de um Cenário</a><br>

![a](../referencias/entr3-cenarios2.png)

Fonte: <a id="REFBIB1" href="#anchor_refbib1">Interação Humano-Computador e Experiência de Usuário, p. 172</a>

---

<a id="anchor_7" href="#REF7">**Imagem 7** ─ Cenário *versus* Caso de Uso</a><br>

![a](../referencias/entr3-cenarios3.png)

Fonte: <a id="REFBIB1" href="#anchor_refbib1">Interação Humano-Computador e Experiência de Usuário, p. 173</a>

</center>

## 📚 Referências Bibliográficas

> <a id="anchor_refbib1" href="#REFBIB1">1.</a> Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. **Interação Humano-Computador e Experiência do usuário**. Autopublicação. 2021. 172-173. ISBN: 978-65-00-19677-1.

> <a id="anchor_refbib2" href="#REFBIB2">2.</a> Leite, Julio C. S. P. **Léxico Ampliado da Linguagem**: Resumo. Disponível em: https://www-di.inf.puc-rio.br/~julio/lal.pdf. Acessado em: 08/12/2024.</a>

## 📑 Histórico de versão

| Versão | Descrição | Autor(es) | Data de Produção | Revisor(es) | Data de Revisão |
| :----: | --------- | --------- | :--------------: | ----------- | :-------------: |
| `1.0`  | Criação do documento  | [João Pedro](https://github.com/JoosPerro) | 06/12/2024 |  |  |
| `1.1`  | Correções e adição de *hyperlinks*  | [João Pedro](https://github.com/JoosPerro) | 08/12/2024 |  |  |
