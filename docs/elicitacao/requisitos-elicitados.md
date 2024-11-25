# Requisitos Elicitados



## Introdução

Requisitos são condições ou capacidades que um sistema (como um aplicativo, por exemplo) deve atender para resolver problemas ou alcançar objetivos, documentando necessidades e restrições. Os requisitos funcionais definem as funcionalidades específicas do sistema, enquanto os não funcionais abrangem qualidades como desempenho, segurança e usabilidade. Implementá-los adequadamente, após sua elicitação por meio de uma ou mais técnicas, é crucial para alinhar o desenvolvimento às expectativas, reduzir custos e retrabalho, garantir qualidade e minimizar falhas, criando sistemas eficazes e alinhados às necessidades dos usuários.

Este documento reúne todos os requisitos, tanto funcionais quanto não funcionais, elicitados através das técnicas de [Análise de Documentos](tecnicas/analise-de-documentos.md), [Grupo de Foco](tecnicas/grupo-de-foco.md), [Introspecção](tecnicas/introspeccao.md), [Observação](tecnicas/observacao.md) e [Questionário](analise-perfil-usuario/questionario.md).



## Metodologia

Optamos por dispor todos os requisitos elicitados na **Tabela 2**. A tabela contém os campos "Tipo", que trata da sigla referente ao tipo de requisito elicitado, "Descrição", onde a funcionalidade do requisito é descrita, "Rastreabilidade", que contém a(s) sigla(s)* referente(s) a cada técnica utilizada durante cada elicitação, e o campo "Implementado", onde é possível identificar se o requisito equivalente foi ou não implementado no Meu SUS Digital.

Já na **Tabela 1**, optamos por disponibilizar uma legenda para cada uma das siglas utilizadas na **Tabela 2**.

\* Cada sigla contém um link que redireciona para o documento respectivo à técnica em questão. 

<div align="center">
    <p><strong>Tabela 1 – Legenda para cada sigla utilizada</strong></p>
</div>

<center>

| Tipo | Descrição |
| :--: | --------- |
| RFn  | n-ésimo Requisito Funcional |
| RNFn | n-ésimo Requisito Não Funcional |
| ADn  | n-ésimo Requisito elicitado pela técnica de Análise de Documentos |
| GFn  | n-ésimo Requisito elicitado pela técnica de Grupo de Foco         |
| INTn | n-ésimo Requisito elicitado pela técnica de Introspecção          |
| OBSn | n-ésimo Requisito elicitado pela técnica de Observação            |
| QUEn | n-ésimo Requisito elicitado pela técnica de Questionário          |

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/algorithmorphic">Artur Ricardo</a>.</p>
</div>



## Requisitos

Na **Tabela 2**, temos a relação de requisitos elicitados para o Meu SUS Digital, bem como sua rastreabilidade (técnicas por meio das quais foram elicitados) e implementação (se foram ou não implementados no Meu SUS Digital). 

<div align="center">
    <p><strong>Tabela 2 – Requisitos elicitados</strong></p>
</div>

<center>

| Tipo | Descrição | Rastreabilidade | Implementado |
| :--: | --------- | --------------- | :----------: |
| RF1   | O sistema deve permitir que o paciente realize login por meio de uma conta Gov.br | OBS1 | $5,00 |
| RF2   | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Vacinas | OBS2 | $1,00 |
| RF3   | O aplicativo deve disponibilizar ao usuário o acesso à sua Carteira Nacional de Vacinação Digital | OBS3 | $5,00 |
| RF4   | O aplicativo deve permitir que o usuário selecione o idioma do certificado referente à sua Carteira Nacional de Vacinação Digital | OBS4 | $1,00 |
| RF5   | O aplicativo deve permitir que o usuário exporte/baixe o certificado referente à sua Carteira Nacional de Vacinação Digital | OBS5 | $5,00 |
| RF6   | O aplicativo deve disponibilizar ao usuário o acesso ao seu histórico de vacinas | OBS6 | $2,00 |
| RF7   | O aplicativo deve disponibilizar ao usuário o acesso aos detalhes de cada vacina | OBS7 | $2,00 |
| RF8   | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Exames | OBS8 | $1,00 |
| RF9   | O aplicativo deve permitir a visualização dos exames laboratoriais realizados | OBS9 | $3,00 |
| RF10  | O aplicativo deve permitir a visualização dos resultados e demais informações a respeito dos exames laboratoriais realizados | OBS10 | $2,00 |
| RF11  | O aplicativo deve permitir a exportação/download do documento contendo o resultado e demais informações a respeito de cada exame laboratorial realizado | OBS11 | $2,00 |
| RF12  | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Medicamentos | OBS12 | $1,00 |
| RF13  | O aplicativo deve disponibilizar ao usuário o acesso ao seu histórico de medicamentos recebidos | OBS13 | $3,00 |
| RF14  | O aplicativo deve permitir que o usuário adicione um medicamento recebido por meio de programas de dispensação do Governo Federal através de um mecanismo de busca | OBS14 | $2,00 |
| RF15  | O aplicativo deve permitir que o usuário possa realizar a busca por um medicamento através do nome e dosagem do mesmo | OBS15 | $1,00 |
| RF16  | O aplicativo deve fornecer ao usuário, em adesão ao Programa Farmácia Popular, a opção de autorizar ou não a retirada de medicamentos em seu CPF | OBS16 | $3,00 |
| RF17  | O aplicativo deve permitir que o usuário possa verificar os medicamentos recebidos pelo Programa Farmácia Popular | OBS17 | $3,00 |
| RF18  | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Dignidade Menstrual | OBS18 | $1,00 |
| RF19  | Caso o usuário atenda aos critérios do Programa, o aplicativo deve permitir que o usuário emita uma autorização para participar do Programa Dignidade Menstrual | OBS19 | $2,00 |
| RF20  | O aplicativo deve permitir que o usuário exporte/baixe o documento referente à autorização de participação do Programa Dignidade Menstrual | OBS20 | $3,00 |
| RF21  | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Rede de Saúde | OBS21 | $1,00 |
| RF22  | O aplicativo deve pedir permissão de acesso à localização do dispositivo do usuário | OBS22 | $1,00 |
| RF23  | O aplicativo deve armazenar a localização do dispositivo do usuário | OBS23 | $0,00 |
| RF24  | O aplicativo deve oferecer opções de estabelecimentos de saúde a fim de que o usuário possa identificar àqueles próximos à sua localização, de acordo com o tipo de serviço desejado | OBS24 | $2,00 |
| RF25  | O aplicativo deve permitir que o usuário possa identificar os estabelecimentos de saúde recentes vinculados a ele | OBS25 | $2,00 |
| RF26  | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Agendamentos | OBS26 | $1,00 |
| RF27  | O aplicativo deve exibir as consultas médicas ou exames de saúde do usuário | OBS27 | $2,00 |
| RF28  | O aplicativo deve possibilitar o agendamento de consultas médicas ou exames de saúde | OBS28 | $4,00 |
| RF29  | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Atendimento e Internação | OBS29 | $1,00 |
| RF30  | O aplicativo deve exibir os registros de atendimentos ou internações do usuário | OBS30 | $1,00 |
| RF31  | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Contatos | OBS31 | $1,00 |
| RF32  | O aplicativo deve exibir contatos de profissionais de saúde | OBS32 | $1,00 |
| RF33  | O aplicativo deve permitir que o usuário adicione o contato de um profissional de saúde em casos de emergência | OBS33 | $1,00 |
| RF34  | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Diário de Saúde | OBS34 | $1,00 |
| RF35  | O aplicativo deve exibir todos os registros de saúde do usuário | OBS35 | $2,00 |
| RF36  | O aplicativo deve exibir os registros de saúde do usuário referentes à sua Pressão | OBS36 | $0,00 |
| RF37  | O aplicativo deve permitir que o usuário adicione um registro de saúde referente à sua Pressão | OBS37 | $1,00 |
| RF38  | O aplicativo deve exibir os registros de saúde do usuário referentes à sua Glicose | OBS38 | $0,00 |
| RF39  | O aplicativo deve permitir que o usuário adicione um registro de saúde referente à sua Glicose | OBS39 | $1,00 |
| RF40  | O aplicativo deve exibir os registros de saúde do usuário referentes ao seu IMC | OBS40 | $0,00 |
| RF41  | O aplicativo deve permitir que o usuário adicione um registro de saúde referente ao seu IMC | OBS41 | $1,00 |
| RF42  | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Alergias | OBS42 | $1,00 |
| RF43  | O aplicativo deve exibir as alergias que usuário possui | OBS43 | $1,00 |
| RF44  | O aplicativo deve permitir que o usuário adicione uma alergia | OBS44 | $1,00 |
| RNF1  | O sistema deve garantir que o login por meio da conta Gov.br seja realizado com autenticação segura (OAuth 2.0) | OBS45 | $1,00 |
| RNF2  | O aplicativo deve exibir informações de ajuda de maneira acessível e compreensível para todos os usuários, incluindo pessoas com deficiência visual ou auditiva | OBS46 | $2,00 |
| RNF3  | O histórico de vacinação deve ser carregado em menos de 3 segundos em dispositivos com conexão 4G | OBS47 | $0,00 |
| RNF4  | O aplicativo deve oferecer suporte a pelo menos três idiomas (português, inglês e espanhol) para os certificados de vacinação | OBS48 | $1,00 |
| RNF5  | O certificado de vacinação deve ser exportado em formato PDF de alta qualidade, com tamanho máximo de 2 MB | OBS49 | $1,00 |
| RNF6  | O histórico de vacinas deve ser armazenado em servidores seguros, em conformidade com a LGPD | OBS50 | $1,00 |
| RNF7  | O acesso aos detalhes de cada vacina deve ser protegido por criptografia ponta a ponta | OBS51 | $0,00 |
| RNF8  | As informações de ajuda relacionadas a exames devem ser exibidas em uma interface amigável, seguindo padrões de usabilidade | OBS52 | $1,00 |
| RNF9  | Os resultados de exames laboratoriais devem ser apresentados em formato padronizado e visualmente acessível | OBS53 | $2,00 |
| RNF10 | Os dados sobre exames laboratoriais devem ser carregados de maneira otimizada, mesmo em conexões lentas | OBS54 | $0,00 |
| RNF11 | Os documentos de resultados de exames laboratoriais devem ser exportados em formatos amplamente compatíveis, como PDF ou JPEG | OBS55 | $1,00 |
| RNF12 | O aplicativo deve exibir informações sobre medicamentos em uma interface responsiva e acessível | OBS56 | $2,00 |
| RNF13 | O histórico de medicamentos deve ser armazenado em servidores redundantes para garantir alta disponibilidade | OBS57 | $0,00 |
| RNF14 | A busca por medicamentos deve apresentar resultados relevantes em menos de 2 segundos | OBS58 | $0,00 |
| RNF15 | A busca de medicamentos por nome e dosagem deve ser sensível a erros de digitação | OBS59 | $1,00 |
| RNF16 | A autorização para retirada de medicamentos deve ser confirmada com autenticação segura do usuário | OBS60 | $1,00 |
| RNF17 | Os medicamentos recebidos pelo Programa Farmácia Popular devem ser exibidos em ordem cronológica | OBS61 | $1,00 |
| RNF18 | A seção de ajuda do Programa Dignidade Menstrual deve seguir diretrizes de acessibilidade (WCAG 2.1) | OBS62 | $0,00 |
| RNF19 | As autorizações para participação no Programa Dignidade Menstrual devem ser processadas em menos de 5 segundos | OBS63 | $0,00 |
| RNF20 | O documento referente à autorização do Programa Dignidade Menstrual deve ser exportado em formato PDF com validação digital | OBS64 | $1,00 |
| RNF21 | A localização do dispositivo do usuário deve ser acessada apenas com consentimento explícito e armazenada temporariamente | OBS65 | $1,00 |
| RNF22 | O aplicativo deve usar APIs de geolocalização eficientes e de baixo consumo de bateria | OBS66 | $0,00 |
| RNF23 | As opções de estabelecimentos de saúde devem ser carregadas em menos de 2 segundos | OBS67 | $0,00 |
| RNF24 | A lista de estabelecimentos de saúde recentes deve ser atualizada automaticamente sem comprometer o desempenho | OBS68 | $1,00 |
| RNF25 | O agendamento de consultas deve ser sincronizado em tempo real com os sistemas do SUS | OBS69 | $1,00 |
| RNF26 | As informações sobre consultas médicas ou exames devem ser exibidas com visualização amigável e intuitiva | OBS70 | $2,00 |
| RNF27 | O registro de atendimentos ou internações deve ser armazenado de forma segura em servidores certificados | OBS71 | $1,00 |
| RNF28 | Os contatos de profissionais de saúde devem ser exibidos em uma lista organizada, de fácil navegação | OBS72 | $1,00 |
| RNF29 | As informações de emergência devem ser acessíveis rapidamente, com opção de busca por nome ou especialidade | OBS73 | $1,00 |
| RNF30 | Os registros de saúde do usuário devem ser apresentados em gráficos interativos e de fácil interpretação | OBS74 | $0,00 |
| RNF31 | As informações sobre Pressão, Glicose e IMC devem ser armazenadas de forma criptografada para garantir a privacidade | OBS75 | $1,00 |
| RNF32 | O aplicativo deve garantir alta disponibilidade, com no mínimo 99,5% de uptime | OBS76 | $0,00 |
| RNF33 | Os dados relacionados a alergias devem ser carregados rapidamente e protegidos contra acesso não autorizado | OBS77 | $1,00 |

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/algorithmorphic">Artur Ricardo</a>.</p>
</div>



## 📚 Bibliografia

> VAZQUEZ, Carlos Eduardo; SIMÕES, Guilherme Siqueira. Engenharia de Requisitos: software orientado ao negócio. Rio de Janeiro: Brasport, 2016.



## 📑 Histórico de Versões

| Versão | Descrição | Autor(es) | Data de Produção | Revisor(es) | Data de Revisão | 
| :----: | --------- | --------- | :--------------: | ----------- | :-------------: |
| `1.0`  | Criação inicial da estrutura do documento referente aos requisitos elicitados. | [Artur Ricardo](https://github.com/algorithmorphic) | 23/11/2024 | [Pedro Lopes](https://github.com/pLopess) | 24/11/2024 |
| `1.1`  | Adição de parte dos requisitos elicitados. | [Artur Ricardo](https://github.com/algorithmorphic) | 23/11/2024 |  |  |
