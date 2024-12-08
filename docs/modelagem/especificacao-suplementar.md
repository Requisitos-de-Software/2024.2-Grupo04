# Especificação Suplementar

## Introdução

A Especificação Suplementar é um documento que detalha requisitos adicionais de um sistema, complementando as informações descritas no Documento de Requisitos. Enquanto o foco principal do Documento de Requisitos está nas funcionalidades que o sistema deve oferecer, a Especificação Suplementar aborda aspectos não funcionais, como desempenho, usabilidade, confiabilidade, suporte e segurança. Além disso, inclui restrições técnicas, padrões a serem seguidos e quaisquer condições específicas que não sejam tratadas diretamente no levantamento inicial de requisitos. Esse documento é essencial para garantir que o sistema atenda às expectativas do cliente e aos padrões necessários para sua operação eficiente.

## Metodologia

Para a criação deste artefato, foram consideradas funcionalidades ainda não implementadas, identificadas por meio das técnicas de elicitação de requisitos realizadas durante o desenvolvimento do projeto. Essas técnicas permitiram coletar informações essenciais diretamente dos *stakeholders*, garantindo que todos os aspectos importantes para o sistema fossem considerados.

Os requisitos relacionados a cada uma dessas funcionalidades foram organizados e classificados de acordo com o modelo **FURPS+**, que é uma estrutura amplamente utilizada para categorizar requisitos de software. Esse modelo divide os requisitos em cinco categorias principais:

- **Funcionalidade (F)**: requisitos relacionados às funções específicas que o sistema deve realizar.
- **Usabilidade (U)**: aspectos ligados à experiência do usuário, como interface e facilidade de uso.
- **Confiabilidade (R)**: atributos que garantem o funcionamento consistente do sistema, como disponibilidade e tolerância a falhas.
- **Desempenho (P)**: requisitos relacionados à velocidade, capacidade de resposta e eficiência do sistema.
- **Suportabilidade (S)**: características que facilitam a manutenção, extensibilidade e portabilidade do sistema.  

O "+" no modelo representa fatores adicionais, como requisitos técnicos, restrições de design, padrões e considerações legais. Essa abordagem sistemática permite uma análise abrangente e estruturada dos requisitos, assegurando que o sistema atenda tanto às necessidades funcionais quanto às características de qualidade esperadas.

## Funcionalidade

Os requisitos funcionais, que foram identificados durante a fase de elicitação, estão detalhados na [Tabela 2](../elicitacao/requisitos-elicitados.md/#requisitos) da seção de [Requisitos Elicitados](../elicitacao/requisitos-elicitados.md). Esta tabela apresenta uma lista de todos os requisitos que foram priorizados.

## Usabilidade

Refere-se à facilidade com que o usuário pode executar uma tarefa utilizando o aplicativo.

<div align="center">
    <p><strong>Tabela 1 – Requisitos de Usabilidade</strong></p>
</div>

<center>

| ID    | Descrição |
| ----- | --------- |
| USA01 | O fluxo para solicitar medicamentos deve ser concluído em até 5 cliques/telas |
| USA02 | O resultado da consulta de pedidos de medicamento deve ser exibido em ordem cronológica |
| USA03 | O resultado da consulta de receitas médicas deve ser exibido em ordem cronológica |

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/MatheusHenrickSantos">Matheus Henrick</a>.</p>
</div>



## Confiabilidade

Refere-se à capacidade do sistema de operar sem falhas, incluindo a frequência com que ocorrem falhas, a eficácia dos mecanismos de recuperação e prevenção, e o intervalo médio entre falhas.

<div align="center">
    <p><strong>Tabela 2 – Requisitos de Confiabilidade</strong></p>
</div>

<center>

| ID    | Descrição |
| ----- | --------- |

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/MatheusHenrickSantos">Matheus Henrick</a>.</p>
</div>


## Desempenho

Refere-se aos critérios operacionais necessários para que os requisitos sejam atendidos, incluindo a velocidade de processamento, os limites máximos e mínimos aceitáveis, o tempo de resposta esperado, bem como as restrições relacionadas às interfaces e funcionalidades do sistema.

<div align="center">
    <p><strong>Tabela 3 – Requisitos de Desempenho</strong></p>
</div>

<center>

| ID    | Descrição |
| ----- | --------- |
| DES01 | A aplicação deve processar a solicitação de medicamentos e fornecer uma resposta em até 5 segundos |
| DES02 | A receita médica deve ser exportada em formato PDF de alta qualidade, com tamanho máximo de 2 MB |

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/MatheusHenrickSantos">Matheus Henrick</a>.</p>
</div>


## Suportabilidade

Abrange os requisitos associados ao suporte e à manutenção do sistema, incluindo aspectos como facilidade de manutenção, possibilidade de modificações e atualizações, documentação completa, além de recursos que promovam a realização de testes e o diagnóstico de problemas de forma eficiente.

<div align="center">
    <p><strong>Tabela 4 – Requisitos de Suportabilidade</strong></p>
</div>

<center>

| ID    | Descrição |
| ----- | --------- |

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/MatheusHenrickSantos">Matheus Henrick</a>.</p>
</div>


## Restrições de Design



## 📚 Bibliografia

> SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 13. 2017. Apresentação de slides. Disponível em: [https://aprender3.unb.br/pluginfile.php/2972480/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf](https://aprender3.unb.br/pluginfile.php/2972480/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf). Acesso em: 4 dez. 2024. 

## 📑 Histórico de Versões

| Versão | Descrição | Autor(es) | Data de Produção | Revisor(es) | Data de Revisão | 
| :----: | --------- | --------- | :--------------: | ----------- | :-------------: |
| `1.0`  | Criação do documento. | [Matheus Henrick](https://github.com/MatheusHenrickSantos) | 02/12/2024 | [Pedro Lopes](https://github.com/pLopess) | 08/12/2024 |
| `1.1`  | Adição de requisitos. | [Matheus Henrick](https://github.com/MatheusHenrickSantos) | 07/12/2024 | [Pedro Lopes](https://github.com/pLopess) | 08/12/2024 |
