# FATEC Profº Jessen Vidal - São José dos Campos - 4º Semestre DSM - 2025

<p>Projeto desenvolvido para a API (Aprendizagem por Projeto Integrado) do 4° Semestre do curso Desenvolvimento de Software Multiplataforma (DSM) em parceria com a Tecsus.</p>

> _A API se trata de um projeto submetido à metodologia de ensino em implantação na Fatec São José dos Campos, do qual os alunos formam equipes baseadas na metodologia ágil SCRUM, tendo um aluno como Scrum Master, um sendo o Product Owner e o restante dos integrantes como Dev Team._

### 📃 Estrutura de Branchs 
  #### Main - Estado principal que armazena a versão estável do projeto
  #### Dev - Estado de desenvolvimento atual
  #### Sprint X - Instancia de todos respositórios ao fim da Sprint X
### ⏳ Status do projeto: 0/3 Sprint

### 📃 Respositórios 
- [Repositório FrontEnd](https://github.com/Equipe-Skyfall/skytrack-front)
- [Respositório BackEnd](https://github.com/Equipe-Skyfall/skytrack-back)
- [Respositório BD](https://github.com/Equipe-Skyfall/skytrack-bd)
- [Respositório Principal](https://github.com/Equipe-Skyfall/skytrack)

---

## 📑 Sumário
- [Visão do Projeto](#visao-do-projeto)
- [Tecnologias utilizadas](#tecnologias)
- [MVP](#mvp)
- [Product Backlog](#backlog)
- [Equipe](#equipe)
- [Sprint Backlog](#backsprint)
---

## 🏥 Dores do Cliente

### Verificar
**Problemas Identificados**:
- **Erros e Inconsistências**: Processos manuais de registro de ponto levam a falhas frequentes, comprometendo a precisão e a rastreabilidade das horas trabalhadas.
- **Falta de Centralização**: A ausência de um sistema centralizado dificulta a gestão de horas extras, férias e folgas, afetando a produtividade e a comunicação entre setores.
- **Ineficiência no Controle de Ponto**: A gestão de marcações e ajustes de jornada é prejudicada pela falta de organização e dados acessíveis.
- **Decisões Estratégicas Prejudicadas**: Sem dados claros e estruturados, as decisões sobre horas extras, banco de horas e planejamento de férias são limitadas, afetando o desempenho da organização.

### Planejar
**Objetivos**:
- **Automação do Controle de Ponto**: Implementar um sistema que minimize a entrada de dados manual, reduzindo erros e melhorando a rastreabilidade das horas trabalhadas.
- **Centralização dos Processos**: Criar um sistema centralizado que permita a integração dos dados de ponto, férias, folgas e horas extras, facilitando a gestão e a tomada de decisões.
- **Melhoria no Controle de Jornadas**: Estruturar um módulo específico para gestão de jornadas flexíveis e ajustes de ponto, tornando os processos mais ágeis e eficientes.
- **Disponibilização de Dados Estratégicos**: Desenvolver relatórios analíticos e dashboards que ofereçam insights sobre horas trabalhadas, horas extras e ausências, suportando decisões estratégicas.

### Controlar
**Ações para Garantir a Efetividade**:
- **Monitoramento do Sistema de Automação**: Avaliar a eficácia da automação implementada, medindo a redução de erros e inconsistências nos registros de ponto.
- **Verificação da Centralização de Dados**: Acompanhar se todos os setores estão utilizando o sistema centralizado de maneira eficiente, garantindo a adesão e facilitando a integração dos processos.
- **Avaliação do Controle de Jornadas**: Monitorar a gestão de jornadas e ajustes de ponto, assegurando que os processos estejam otimizados.
- **Análise dos Relatórios Estratégicos**: Revisar regularmente os relatórios para garantir que os dados ofereçam insights relevantes, possibilitando ajustes rápidos nas estratégias de gestão de horas e férias.

---

## 👁 Visão do Projeto <a name="visao-do-projeto"></a>
<p>Nosso projeto é um Sistema de Coleta de Dados Meteorológico em Tempo Real, com foco na prevenção de riscos e desastres naturais. A plataforma visa centralizar e analisar informações, como índices de chuva, captadas por uma rede de sensores de baixo custo. Será incluso um modelo dinâmico para a aceitação de diversos tipos de estações, facilitando a obtenção de dados oriundos de diversas fontes. As informações serão exibidas em um painel de controle moderno e intuitivo, enquanto um sistema de notificações proativo alertará os usuários sobre potenciais riscos, como inundações e deslizamentos. O sistema também incluirá um espaço de conteúdo educacional, expondo de forma clara a lógica utilizada pelo sistema para captação de dados e informações estimadas.</p>

---

## 💻 Tecnologias utilizadas <a name="tecnologias"></a>
<div align="center">
<img src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=black&color=06b6d4">
<img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=black&color=06b6d4">
<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=black&color=06b6d4">
<img src="https://img.shields.io/badge/Jira-217346?style=for-the-badge&logo=Jira&logoColor=black&color=06b6d4">
<img src="https://img.shields.io/badge/Microsoft_Teams-6264A7?style=for-the-badge&logo=microsoft-teams&logoColor=black&color=06b6d4">
<img src="https://img.shields.io/badge/typescript-000000?style=for-the-badge&logo=typescript&logoColor=black&color=06b6d4">
<img src="https://img.shields.io/badge/react-000000?style=for-the-badge&logo=react&logoColor=black&color=06b6d4">
<img src="https://img.shields.io/badge/tailwind-000000?style=for-the-badge&logo=tailwindcss&logoColor=black&color=06b6d4">
</div>

## 💻 Padrões de commit

**FEAT**: Adiciona um novo recurso ou funcionalidade.
  Exemplo: FEAT - Adição da navbar

**FIX**: Corrige um bug.
  Exemplo: FIX - Corrige o modal que não estava fechando

**CHORE**: Atualizações de manutenção que não alteram a lógica de negócio ou visual, como atualização de dependências, configurações de build, etc.
  Exemplo: CHORE - Atualização das dependências do Node.js

**DOCS**: Altera a documentação, como o README, comentários no código ou arquivos de documentação do projeto.
  Exemplo: DOCS - Atualiza README com informações sobre novas rotas

**STYLE**: Modifica a formatação do código, como espaços em branco, quebra de linha ou pontuação, sem alterar a lógica.
  Exemplo: STYLE - Adiciona comentários no código para facilitar a leitura

**REFACTOR**: Refatora o código sem adicionar novas funcionalidades ou corrigir bugs, visando melhorar a estrutura, legibilidade ou desempenho.
  Exemplo: REFACTOR - Refatora o código, deixando-o mais leve

**TEST**: Adiciona, modifica ou remove testes unitários ou de integração.
  Exemplo: TEST - Adiciona teste para o componente de login

**PERF**: Melhora a performance.
Exemplo: PERF - Otimiza a execução de consultas no banco de dados

**BUILD**: Altera o sistema de build ou as dependências externas, como npm, gradle, ou docker.
  Exemplo: BUILD - Adiciona um Dockerfile para o ambiente de produção

**REVERT**: Reverte um commit anterior.
  Exemplo: REVERT - Reverte a adição de autenticação de middleware

**HOTFIX**: Corrige um bug crítico em produção de forma urgente.
  Exemplo: HOTFIX - Corrige vulnerabilidade crítica na autenticação de usuários

Convenções Adicionais

Nomenclatura de Variáveis: Utiliza-se o padrão camelCase (ex: nomeCompleto).

---


## 📜 Product Backlog <a name="backlog"><a>

| RANK | SPRINT | PRIORIDADE | ESTIMATIVA | USER STORY (NOME)                                             | STATUS |
|:----:|:------:|:----------:|:----------:|:-------------------------------------------------------------:|:------:|
| 1    |      |             |            | Como Administrador, quero um CRUD para as estações, para gerenciamento de suas informações.|        |
| 2    |      |             |            | Como Usuário Público, quero visualizar a lista de estações, para que eu saiba qual é a estação dos dados exibidos.|        |
| 3    |      |             |            | Como Administrador, quero um CRUD para os parâmetros utilizados nas estações, para manusear os dados de maneira adequada.|        |
| 4    |      |             |            | Como Administrador, quero um CRUD para os alertas de condições meteorológicas, para gerar notificações com base em informações meteorológicas.|        |
| 5    |      |             |            | Como Usuário Público, quero que seja possível receber alertas relevantes, para que eu saiba quando condições perigosas ocorrerem.|        |
| 6    |      |             |            | Como Administrador, quero um CRUD para os usuários da aplicação, para melhor gerênciamento de acesso.|        |
| 7    |      |             |            | Como Cliente, quero um controle de acesso que diferencie as permissões do Administrador e do Usuário Público, para que tenha segurança no gerênciamento de informações do sistema.|        |
| 8    |      |             |            | Como Usuário Público, quero acessar um Dashboard de informações, para que eu compreenda os dados meteorológicos facilmente.|        |
| 9    |      |             |            | Como Usuário, eu quero visualizar conceitos estatísticos nos dashboards, para análises mais precisas.|        |
| 10    |      |             |            | Como Administrador, quero poder editar as informações exibidas no Dashboard, para dados de minha escolha.|        |
| 11    |      |             |            | Como Administrador, quero gerar relatórios detalhados, para que seja possível a geração de insights.|        |
| 12    |      |             |            | Como Usuário Público, quero acessar relatórios prontos em PDF, para que eu possa utilizar como fonte de dados.|        |
| 13   |      |             |            | Como Usuário Público, quero acessar um guia explicativo sobre cada parâmetro meteorológico, incluindo as fórmulas utilizadas, para que eu aprenda o que significam os dados coletados.|        |
| 14   |      |             |            | Como Administrador, quero processar e armazenar automaticamente os dados recebidos por meio de um datalogger, para que eles fiquem disponíveis no Dashboard|        |
| 15   |      |             |            | Como Cliente, quero que o sistema tenha um modelo dinâmico que seja capaz de receber e registrar diversas estações com sensores diferentes, para a possibilidade de receber os dados de diversas fontes.|        |
| 16   |      |             |            | Como Administrador, quero consultar o histórico de alertas gerados. Para que eu entenda os padrões de ocorrências.|        |
| 17   |      |             |            | Como Cliente, quero uma estação meteorológica física montada com sensores. para que os dados sejam coletados em tempo real e enviados ao sistema.|        |
| 18   |      |             |            | Como Administrador, quero que o sistema tenha um serviço de recepção de dados a cada periodo de tempo, para que múltiplas estações enviem informações sem perda.|        |



---

## 📝 Sprint Backlog <a name="backsprint"><a>


### [Clique aqui para ser redirecionado](https://github.com/DuuhZero/backlog/tree/main/docs)

---

## 👥 Equipe <a name="equipe"><a>
|  Foto        |     Função    |           Nome            |                            LinkedIn                            |                      GitHub                       |
| :----: | :-----------: | :-----------------------: | :------------------------------------------------------------: | :-----------------------------------------------: |
| <img src="https://avatars.githubusercontent.com/u/160733714?v=4" width="75px"> | Dev Team  | Eduardo da Silva Fontes | [Linkedin](https://www.linkedin.com/in/eduardo-da-silva-fontes/)  | [GitHub](https://github.com/DuuhZero)           |
| <img src="https://avatars.githubusercontent.com/u/161594793?v=4" width="75px"> | Dev Team      | Eric Kawata |  [Linkedin](https://www.linkedin.com/in/eric-kawata-99678b302/)  | [GitHub](https://github.com/ericFatec)    |
| <img src="https://avatars.githubusercontent.com/u/144804717?v=4" width="75px"> | Dev Team      | Fábio Hiroshi |  [Linkedin](https://www.linkedin.com/in/f%C3%A1bio-hiroshi-5393a51a0)  | [GitHub](https://github.com/FabioHiros)    |
| <img src="https://avatars.githubusercontent.com/u/119539664?v=4" width="75px">|Product Owner| João Pedro França Alves de Souza |  [Linkedin](https://www.linkedin.com/in/joão-pedro-frança-alves-de-souza-8700a62b3/)  | [GitHub](https://github.com/jofran2001)  |
| <img src="https://avatars.githubusercontent.com/u/162117916?v=4" width="75px"> | Dev Team  | João Vitor Rossi Ferreira |  [Linkedin](https://www.linkedin.com/in/joão-rossi-7311a0301/)  | [GitHub](https://github.com/joaorossiferreira)    |
| <img src="https://avatars.githubusercontent.com/u/95691713?v=4" width="75px"> | Dev Team      | Kathellyn Caroline Alves dos Santos |  [Linkedin](https://www.linkedin.com/in/kathellyn-caroline-a562101b9)  | [GitHub](https://github.com/CarolineKathellyn)    |
| <img src="https://avatars.githubusercontent.com/u/162117908?v=4" width="75px"> | Dev Team      | Paulo Henrique Martins de Almeida |  [Linkedin](https://www.linkedin.com/in/paulo-almeida-3102452a7/)  | [GitHub](https://github.com/pauloalmeida46)    |
| <img src="https://avatars.githubusercontent.com/u/161987258?v=4" width="75px"> | Scrum Master      | Victor Daniel |  [Linkedin](https://www.linkedin.com/in/victor-daniel-ramos-bessa-1436a3215/)  | [GitHub](https://github.com/victordanielrb)    |


