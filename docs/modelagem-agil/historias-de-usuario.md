# Histórias de Usuário

## Introdução



## Metodologia

A metodologia adotada para a elaboração deste documento foi baseada na divisão colaborativa do trabalho entre os membros da equipe, de forma a assegurar o equilíbrio entre eficiência no desenvolvimento e o aprendizado individual de cada integrante.

#### Divisão de Requisitos
  
Os requisitos funcionais foram distribuídos entre os integrantes da equipe, com cada membro sendo responsável por desenvolver dez histórias de usuário. Esse modelo permitiu distribuir a carga de trabalho equitativamente e promover um entendimento mais profundo de diferentes aspectos do sistema por parte de cada integrante.

#### Definição de Critérios de Aceitação

Como forma de assegurar a qualidade das histórias de usuário sem comprometer o ritmo de trabalho, foi estipulado que ao menos cinco critérios de aceitação fossem definidos por integrante. Essa flexibilização visa atender ao cronograma de desenvolvimento enquanto mantém um padrão mínimo de detalhamento e clareza nas histórias de usuário.

#### Documentação das Histórias de Usuário

Na **Tabela 1**, podemos identificar a legenda para cada uma das siglas utilizadas por todo o documento, principalmente nas tabelas.

<div align="center">
    <p><strong>Tabela 1 – Legenda para cada sigla utilizada</strong></p>
</div>

<center>

| Tipo | Descrição                   |
| :--: | --------------------------- |
| HUn  | n-ésima História de Usuário |
| RFn  | n-ésimo Requisito Funcional |

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/MatheusHenrickSantos">Matheus Henrick</a>.</p>
</div>

Quanto ao formato das histórias de usuário, estas foram documentadas no formato disposto na **Tabela 2**. 

<div align="center">
    <p><strong>Tabela 2 – Modelo para Histórias de Usuário</strong></p>
</div>

<center>

| *HUn*                 | *Título*                                                                                                   |
| --------------------- | ---------------------------------------------------------------------------------------------------------- |
| Declaração            | Eu, *como* (tipo de usuário), *desejo* (ação) *para* (objetivo/benefício).                                 |
| Critério de Aceitação | *Dado que* (contexto ou lista de condições), *Quando* (evento/ação/gatilho), *Então* (resultado esperado). |
| Prioridade            | (Muito Alta, Alta, Média, Baixa)                                                                           |
| Rastreabilidade       | [RFn](../elicitacao/requisitos-elicitados.md#requisitos/)                                                  |

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/MatheusHenrickSantos">Matheus Henrick</a>.</p>
</div>

Essa abordagem pragmática busca equilibrar qualidade, aprendizado e avanço contínuo do projeto.

## Histórias de Usuário

Abaixo, podemos identificar cada uma das histórias de usuário desenvolvidas por cada integrante da equipe:


---

### HU1 - Login via Gov.br

??? note "Tabela 1 - História de Usuário referente ao login via Gov.br"
    <div align="center">
        <p><strong>Tabela 1 – História de Usuário referente ao login via Gov.br</strong></p>
    </div>

    | **HU1**                   | Login via Gov.br |
    | ------------------------- | ---------------- |
    | **Declaração**            | Eu, _como_ paciente, _desejo_ realizar login por meio de uma conta Gov.br _para_ acessar meus dados no aplicativo. |
    | **Critério de Aceitação** | _Dado que_ o paciente possui uma conta Gov.br, _quando_ acessar a página de login pelo aplicativo, _então_ será possível autenticar-se usando as credenciais Gov.br. |
    | **Prioridade**            | Muito Alta |
    | **Rastreabilidade**       | [RF1](../elicitacao/requisitos-elicitados.md#RF1) |

    <div align="center">
        <p>Autor: <a href="https://github.com/algorithmorphic">Artur Ricardo</a>.</p>
    </div>

### HU11 - Exportação de Resultado de Exame

??? note "Tabela 13 - História de Usuário referente à Exportação de Resultado de Exame"
    <div align="center">
        <p><strong>Tabela 13 – História de Usuário referente à Exportação de Resultado de Exame</strong></p>
    </div>

    | **HU11**                   | Exportação de Resultado de Exame |
    | ------------------------- | ---------------- |
    | **Declaração**            | Eu, como paciente, desejo realizar a busca por um medicamento utilizando seu nome e dosagem para localizar rapidamente as informações desejadas. |
    | **Critério de Aceitação** | <ul> <li>Dado que o usuário esteja na seção de busca de medicamentos</li>  <li>Quando o usuário inserir o nome completo ou parcial do medicamento</li> <li>E a dosagem desejada </li> <li>Então o aplicativo deve:</li> <ul> <li>Retornar uma lista de medicamentos correspondentes à busca,</li> <li>Exibir informações relevantes, como nome completo, dosagem disponível e descrição,</li> <li>Permitir que o usuário selecione o medicamento para visualizar mais detalhes ou realizar ações adicionais. </ul> </li> </ul>|
    | **Prioridade**            |  |
    | **Rastreabilidade**       | [RF11](../elicitacao/requisitos-elicitados.md#RF11) |

    <div align="center">
        <p>Autor: <a href="https://github.com/pLopess">Pedro Lopes</a>.</p>
    </div>

### HU12 - Ajuda Informativa sobre a Seção de Medicamentos

??? note "Tabela 14 - História de Usuário referente à Ajuda Informativa sobre a Seção de Medicamentos"
    <div align="center">
        <p><strong>Tabela 14 – História de Usuário referente à Ajuda Informativa sobre a Seção de Medicamentos</strong></p>
    </div>

    | **HU12**                   | Ajuda Informativa sobre a Seção de Medicamentos |
    | ------------------------- | ---------------- |
    | **Declaração**            | Eu, como paciente, desejo obter ajuda informativa sobre a seção de Medicamentos para entender melhor as funcionalidades e informações disponíveis nessa seção. |
    | **Critério de Aceitação** | <ul> <li>Dado que o paciente esteja navegando na seção de Medicamentos</li> <li>E deseje mais informações ou orientações</li> <li>Quando o paciente clicar na opção "Ajuda" ou no ícone correspondente</li> <li>Então o aplicativo deve:</li> <ul> <li>Exibir um guia informativo ou FAQ relacionado à seção de Medicamentos,</li> <li>Permitir que o paciente visualize detalhes sobre as funcionalidades e o uso da seção,</li> <li>Oferecer exemplos ou links para mais informações, se aplicável.</li> </ul> </li> </ul> |
    | **Prioridade**            |  |
    | **Rastreabilidade**       | [RF12](../elicitacao/requisitos-elicitados.md#RF12) |

    <div align="center">
        <p>Autor: <a href="https://github.com/pLopess">Pedro Lopes</a>.</p>
    </div>


### HU13 - Acesso ao Histórico de Medicamentos Recebidos

??? note "Tabela 15 - História de Usuário referente ao Acesso ao Histórico de Medicamentos Recebidos"
    <div align="center">
        <p><strong>Tabela 15 – História de Usuário referente ao Acesso ao Histórico de Medicamentos Recebidos</strong></p>
    </div>

    | **HU13**                   | Acesso ao Histórico de Medicamentos Recebidos |
    | ------------------------- | ---------------- |
    | **Declaração**            | Eu, como paciente, desejo acessar meu histórico de medicamentos recebidos para consultar informações sobre tratamentos realizados anteriormente. |
    | **Critério de Aceitação** | <ul> <li>Dado que o paciente esteja autenticado no aplicativo</li> <li>E tenha um histórico de medicamentos registrados</li> <li>Quando o paciente acessar a opção "Histórico de Medicamentos" no menu ou seção correspondente</li> <li>Então o aplicativo deve:</li> <ul> <li>Exibir uma lista detalhada com os medicamentos recebidos,</li> <li>Apresentar informações como nome do medicamento, data de recebimento e dosagem,</li> <li>Permitir a ordenação ou filtragem por data ou tipo de medicamento.</li> </ul> </li> </ul> |
    | **Prioridade**            |  |
    | **Rastreabilidade**       | [RF13](../elicitacao/requisitos-elicitados.md#RF13) |

    <div align="center">
        <p>Autor: <a href="https://github.com/pLopess">Pedro Lopes</a>.</p>
    </div>

### HU14 - Adicionar Medicamento Recebido via Programas do Governo Federal

??? note "Tabela 16 - História de Usuário referente à Adição de Medicamento Recebido via Programas do Governo Federal"
    <div align="center">
        <p><strong>Tabela 16 – História de Usuário referente à Adição de Medicamento Recebido via Programas do Governo Federal</strong></p>
    </div>

    | **HU14**                   | Adicionar Medicamento Recebido via Programas do Governo Federal |
    | ------------------------- | ---------------- |
    | **Declaração**            | Eu, como paciente, desejo adicionar um medicamento recebido por meio de programas de dispensação do Governo Federal utilizando um mecanismo de busca para manter meu histórico de medicamentos atualizado de forma prática e precisa. |
    | **Critério de Aceitação** | <ul> <li>Dado que o paciente esteja autenticado no aplicativo</li> <li>E esteja na seção para adicionar medicamentos</li> <li>Quando o paciente acessar o mecanismo de busca</li> <li>E inserir o nome ou informações relacionadas ao medicamento</li> <li>Então o aplicativo deve:</li> <ul> <li>Apresentar sugestões de medicamentos com base na busca,</li> <li>Permitir que o usuário selecione o medicamento correto,</li> <li>Solicitar a confirmação das informações (como data de recebimento e quantidade),</li> <li>Registrar o medicamento no histórico do usuário após a confirmação.</li> </ul> </li> </ul> |
    | **Prioridade**            |  |
    | **Rastreabilidade**       | [RF14](../elicitacao/requisitos-elicitados.md#RF14) |

    <div align="center">
        <p>Autor: <a href="https://github.com/pLopess">Pedro Lopes</a>.</p>
    </div>


### HU15 - Buscar Medicamento por Nome e Dosagem

??? note "Tabela 17 - História de Usuário referente à Busca de Medicamento por Nome e Dosagem"
    <div align="center">
        <p><strong>Tabela 17 – História de Usuário referente à Busca de Medicamento por Nome e Dosagem</strong></p>
    </div>

    | **HU15**                   | Buscar Medicamento por Nome e Dosagem |
    | ------------------------- | ---------------- |
    | **Declaração**            | Eu, como paciente, desejo realizar a busca por um medicamento utilizando seu nome e dosagem para localizar rapidamente as informações desejadas. |
    | **Critério de Aceitação** | <ul> <li>Dado que o paciente esteja na seção de busca de medicamentos</li> <li>Quando o paciente inserir o nome completo ou parcial do medicamento</li> <li>E a dosagem desejada</li> <li>Então o aplicativo deve:</li> <ul> <li>Retornar uma lista de medicamentos correspondentes à busca,</li> <li>Exibir informações relevantes, como nome completo, dosagem disponível e descrição,</li> <li>Permitir que o paciente selecione o medicamento para visualizar mais detalhes ou realizar ações adicionais.</li> </ul> </li> </ul> |
    | **Prioridade**            |  |
    | **Rastreabilidade**       | [RF15](../elicitacao/requisitos-elicitados.md#RF15) |

    <div align="center">
        <p>Autor: <a href="https://github.com/pLopess">Pedro Lopes</a>.</p>
    </div>

### HU16 - Autorizar Retirada de Medicamentos pelo CPF no Programa Farmácia Popular

??? note "Tabela 18 - História de Usuário referente à Autorização de Retirada de Medicamentos pelo CPF"
    <div align="center">
        <p><strong>Tabela 18 – História de Usuário referente à Autorização de Retirada de Medicamentos pelo CPF</strong></p>
    </div>

    | **HU16**                   | Autorizar Retirada de Medicamentos pelo CPF no Programa Farmácia Popular |
    | ------------------------- | ---------------- |
    | **Declaração**            | Eu, como paciente, desejo ter a opção de autorizar ou não a retirada de medicamentos em meu CPF para garantir o controle sobre quem pode acessar meus benefícios do Programa Farmácia Popular. |
    | **Critério de Aceitação** | <ul> <li>Dado que o paciente esteja autenticado no aplicativo</li> <li>Quando o paciente acessar a opção relacionada ao Programa Farmácia Popular</li> <li>Então o aplicativo deve:</li> <ul> <li>Exibir uma opção clara para autorizar ou não a retirada de medicamentos pelo CPF,</li> <li>Permitir que o paciente altere sua escolha a qualquer momento,</li> <li>Registrar a autorização ou recusa de forma segura e acessível para futuras consultas.</li> </ul> </li> </ul> |
    | **Prioridade**            |  |
    | **Rastreabilidade**       | [RF16](../elicitacao/requisitos-elicitados.md#RF16) |

    <div align="center">
        <p>Autor: <a href="https://github.com/pLopess">Pedro Lopes</a>.</p>
    </div>

### HU17 - Verificar Medicamentos Recebidos pelo Programa Farmácia Popular

??? note "Tabela 19 - História de Usuário referente à Verificação de Medicamentos Recebidos pelo Programa Farmácia Popular"
    <div align="center">
        <p><strong>Tabela 19 – História de Usuário referente à Verificação de Medicamentos Recebidos pelo Programa Farmácia Popular</strong></p>
    </div>

    | **HU17**                   | Verificar Medicamentos Recebidos pelo Programa Farmácia Popular |
    | ------------------------- | ---------------- |
    | **Declaração**            | Eu, como paciente, desejo poder verificar os medicamentos recebidos pelo Programa Farmácia Popular para acompanhar meu histórico de utilização e garantir a organização do tratamento. |
    | **Critério de Aceitação** | <ul> <li>Dado que o paciente esteja autenticado no aplicativo</li> <li>Quando o paciente acessar a opção de histórico no Programa Farmácia Popular</li> <li>Então o aplicativo deve:</li> <ul> <li>Exibir uma lista com os medicamentos recebidos, incluindo a data e local da retirada,</li> <li>Organizar as informações de forma clara e ordenada por data,</li> <li>Permitir ao paciente filtrar os registros por período ou tipo de medicamento.</li> </ul> </li> </ul> |
    | **Prioridade**            |  |
    | **Rastreabilidade**       | [RF17](../elicitacao/requisitos-elicitados.md#RF17) |

    <div align="center">
        <p>Autor: <a href="https://github.com/pLopess">Pedro Lopes</a>.</p>
    </div>


### HU18 - Obter Ajuda Informativa sobre a Seção de Dignidade Menstrual

??? note "Tabela 20 - História de Usuário referente à Obtenção de Ajuda Informativa sobre a Seção de Dignidade Menstrual"
    <div align="center">
        <p><strong>Tabela 20 – História de Usuário referente à Obtenção de Ajuda Informativa sobre a Seção de Dignidade Menstrual</strong></p>
    </div>

    | **HU18**                   | Obter Ajuda Informativa sobre a Seção de Dignidade Menstrual |
    | ------------------------- | ---------------- |
    | **Declaração**            | Eu, como paciente, desejo obter ajuda informativa sobre a seção de Dignidade Menstrual para compreender melhor os recursos e serviços disponíveis nessa seção. |
    | **Critério de Aceitação** | <ul> <li>Dado que o paciente esteja autenticado no aplicativo</li> <li>Quando o paciente acessar a opção de ajuda informativa na seção de Dignidade Menstrual</li> <li>Então o aplicativo deve:</li> <ul> <li>Exibir informações claras e relevantes sobre os recursos disponíveis,</li> <li>Incluir orientações sobre como acessar os serviços ou benefícios relacionados,</li> <li>Permitir ao paciente navegar para links ou documentos adicionais para mais detalhes.</li> </ul> </li> </ul> |
    | **Prioridade**            |  |
    | **Rastreabilidade**       | [RF18](../elicitacao/requisitos-elicitados.md#RF18) |

    <div align="center">
        <p>Autor: <a href="https://github.com/pLopess">Pedro Lopes</a>.</p>
    </div>

### HU19 - Emissão de Autorização para Participar do Programa Dignidade Menstrual

??? note "Tabela 21 - História de Usuário referente à Emissão de Autorização para Participar do Programa Dignidade Menstrual"
    <div align="center">
        <p><strong>Tabela 21 – História de Usuário referente à Emissão de Autorização para Participar do Programa Dignidade Menstrual</strong></p>
    </div>

    | **HU19**                   | Emissão de Autorização para Participar do Programa Dignidade Menstrual |
    | ------------------------- | ---------------- |
    | **Declaração**            | Eu, como paciente, desejo emitir uma autorização para participar do Programa Dignidade Menstrual caso atenda aos critérios do programa, para garantir minha participação e acessar os benefícios oferecidos. |
    | **Critério de Aceitação** | <ul> <li>Dado que o paciente esteja autenticado no aplicativo</li> <li>E atenda aos critérios do Programa Dignidade Menstrual</li> <li>Quando o paciente acessar a opção relacionada ao programa no aplicativo</li> <li>Então o aplicativo deve:</li> <ul> <li>Exibir uma opção para emitir a autorização de participação no programa,</li> <li>Confirmar a elegibilidade do paciente antes de permitir a emissão da autorização,</li> <li>Registrar a autorização emitida e fornecer um documento ou comprovante para o paciente.</li> </ul> </li> </ul> |
    | **Prioridade**            |  |
    | **Rastreabilidade**       | [RF19](../elicitacao/requisitos-elicitados.md#RF19) |

    <div align="center">
        <p>Autor: <a href="https://github.com/pLopess">Pedro Lopes</a>.</p>
    </div>


### HU20 - Exportação/Download do Documento de Autorização para o Programa Dignidade Menstrual

??? note "Tabela 22 - História de Usuário referente à Exportação/Download do Documento de Autorização para o Programa Dignidade Menstrual"
    <div align="center">
        <p><strong>Tabela 22 – História de Usuário referente à Exportação/Download do Documento de Autorização para o Programa Dignidade Menstrual</strong></p>
    </div>

    | **HU20**                   | Exportação/Download do Documento de Autorização para o Programa Dignidade Menstrual |
    | ------------------------- | ---------------- |
    | **Declaração**            | Eu, como paciente, desejo exportar ou baixar o documento referente à autorização de participação no Programa Dignidade Menstrual, para ter uma cópia em formato digital ou imprimir para meus registros. |
    | **Critério de Aceitação** | <ul> <li>Dado que o paciente tenha emitido a autorização para o Programa Dignidade Menstrual</li> <li>Quando o paciente acessar a opção de exportar ou baixar o documento</li> <li>Então o aplicativo deve:</li> <ul> <li>Gerar o documento no formato PDF ou outro formato apropriado,</li> <li>Iniciar o download automaticamente no dispositivo do paciente,</li> <li>Exibir uma mensagem de confirmação de sucesso ao concluir o processo de download.</li> </ul> </li> </ul> |
    | **Prioridade**            |  |
    | **Rastreabilidade**       | [RF20](../elicitacao/requisitos-elicitados.md#RF20) |

    <div align="center">
        <p>Autor: <a href="https://github.com/pLopess">Pedro Lopes</a>.</p>
    </div>




## 📚 Bibliografia



## 📑 Histórico de Versões

| Versão | Descrição | Autor(es) | Data de Produção | Revisor(es) | Data de Revisão | 
| :----: | --------- | --------- | :--------------: | ----------- | :-------------: |
| `1.0` | Criação do documento. | [Matheus Henrick](https://github.com/MatheusHenrickSantos) | 12/12/2024 | [Pedro Lopes](https://github.com/pLopess) | 14/12/2024 |
| `1.1` | Adição da metodologia. | [Matheus Henrick](https://github.com/MatheusHenrickSantos) | 13/12/2024 | [Pedro Lopes](https://github.com/pLopess) | 14/12/2024 |
| `1.2` | Correção de titulos das tabelas e novo modelo de tabela expansiva. | [Pedro Lopes](https://github.com/pLopess) | 14/12/2024 | [Artur Ricardo](https://github.com/algorithmorphic) | 15/12/2024 |
| `1.3` | Criando Histórias de Usuário. | [Pedro Lopes](https://github.com/pLopess) | 14/12/2024 | [Artur Ricardo](https://github.com/algorithmorphic) | 15/12/2024 |
| `1.4` | Atualização de siglas, títulos e formatação das tabelas. | [Artur Ricardo](https://github.com/algorithmorphic) | 15/12/2024 | [Pedro Lopes](https://github.com/pLopess) | 15/12/2024 |
| `1.5` | Atualização na parte de documentação das histórias de usuário e demais alterações na ordem e conteúdo do documento. | [Artur Ricardo](https://github.com/algorithmorphic) | 15/12/2024 | [Pedro Lopes](https://github.com/pLopess) | 15/12/2024 |
| `1.6` | Adição de história de usuário e adoção de padrão. | [Artur Ricardo](https://github.com/algorithmorphic) | 15/12/2024 | [Pedro Lopes](https://github.com/pLopess) | 15/12/2024 |