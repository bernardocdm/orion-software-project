# 🚗 Orion AutoWorks 🔧

**Sistema de Gestão para Oficinas Mecânicas** — projeto acadêmico desenvolvido para a disciplina **Projeto de Software**, com foco em modelagem, arquitetura de software e documentação UML.

---

## 🚧 Status do Projeto

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)
![PlantUML](https://img.shields.io/badge/UML-PlantUML-blue)
![Disciplina](https://img.shields.io/badge/PUC%20Minas-Projeto%20de%20Software-red)
![Licença](https://img.shields.io/badge/license-MIT-green)

---

## 📚 Índice

- [Sobre o Projeto](#-sobre-o-projeto)
- [Objetivo](#-objetivo)
- [Principais Funcionalidades](#-principais-funcionalidades)
- [Atores do Sistema](#-atores-do-sistema)
- [Arquitetura](#-arquitetura)
- [Diagramas](#-diagramas)
- [Estrutura do Repositório](#-estrutura-do-repositório)
- [Ferramentas Utilizadas](#-ferramentas-utilizadas)
- [Documentações Utilizadas](#-documentações-utilizadas)
- [Autores](#-autores)
- [Licença](#-licença)

---

## 📝 Sobre o Projeto

O **Orion AutoWorks** é um sistema de gestão para oficinas mecânicas desenvolvido como projeto acadêmico da disciplina **Projeto de Software** do curso de Engenharia de Software da **PUC Minas**.

A proposta do sistema é digitalizar e centralizar os principais processos de uma oficina, substituindo controles manuais e planilhas por uma plataforma integrada de gerenciamento. O sistema contempla funcionalidades relacionadas ao cadastro de clientes e veículos, gerenciamento de ordens de serviço, elaboração de orçamentos e controle de estoque de peças.

Este repositório concentra toda a documentação arquitetural do projeto, incluindo diagramas UML desenvolvidos em **PlantUML**, modelos de dados e especificações de projeto.

---

## 🎯 Objetivo

O Orion AutoWorks tem como propósito digitalizar os principais processos de uma oficina mecânica, oferecendo uma solução para:

- Cadastro e gerenciamento de clientes;
- Cadastro e histórico de veículos;
- Criação e acompanhamento de Ordens de Serviço (OS);
- Geração e aprovação de orçamentos;
- Controle de estoque de peças;
- Registro do andamento e conclusão das manutenções.

---

## ✨ Principais Funcionalidades

- 👤 **Gestão de Clientes:** cadastro e consulta de clientes.
- 🚘 **Gestão de Veículos:** associação de veículos aos seus proprietários.
- 📋 **Ordens de Serviço:** abertura, acompanhamento e finalização de OS.
- 💰 **Orçamentos:** criação, aprovação ou rejeição pelo cliente.
- 🔩 **Controle de Estoque:** gerenciamento de peças utilizadas nas manutenções.
- 📊 **Histórico de Manutenções:** registro das intervenções realizadas em cada veículo.
- 🔐 **Gerenciamento de Usuários:** controle de acesso para atendentes, mecânicos e administradores.

---

## 👥 Atores do Sistema

| Ator | Responsabilidade |
|------|------------------|
| **Cliente** | Solicita serviços, acompanha o andamento e aprova ou rejeita orçamentos. |
| **Atendente** | Realiza cadastros, cria ordens de serviço e gera orçamentos. |
| **Mecânico** | Executa os serviços e atualiza o status das manutenções. |
| **Administrador** | Gerencia usuários, estoque, relatórios e configurações gerais do sistema. |

---

## 🏗 Arquitetura

O Orion AutoWorks adota uma arquitetura **cliente-servidor em três camadas**, composta por:

- **Camada de Apresentação:** Interface Web utilizada pelos atores do sistema;
- **Camada de Aplicação:** responsável pelas regras de negócio, gerenciamento de ordens de serviço, usuários e estoque;
- **Camada de Persistência:** banco de dados relacional responsável pelo armazenamento das informações.

O projeto foi modelado utilizando boas práticas de Engenharia de Software e conceitos de orientação a objetos, servindo como base para uma futura implementação.

---

## 📐 Diagramas

Todos os diagramas foram desenvolvidos utilizando **PlantUML** e estão organizados por categoria.

| Tipo de Diagrama | Localização |
|------------------|------------|
| Arquitetura | `plantuml/arquitetura/` |
| Casos de Uso | `plantuml/casos-de-uso/` |
| Classes | `plantuml/classes/` |
| Componentes | `plantuml/componentes/` |
| Implantação | `plantuml/implantacao/` |
| Sequência do Sistema (DSS) | `plantuml/sequencia/` |
| Comunicação | `plantuml/comunicacao/` |
| Estados | `plantuml/estados/` |
| Modelo de Dados | `plantuml/dados/` |

### Diagramas presentes no projeto

- ✅ Diagrama de Casos de Uso
- ✅ Diagramas de Sequência do Sistema (3 DSS)
- ✅ Diagramas de Comunicação
- ✅ Diagrama de Classes
- ✅ Diagrama de Componentes
- ✅ Diagrama de Implantação
- ✅ Diagrama de Estados
- ✅ Diagrama de Arquitetura
- ✅ Modelo de Dados e Estratégia de Mapeamento ORM

---

## 📂 Estrutura do Repositório

```text
orion-software-project/
│
├── docs/
│   └── Documentacao_Orion_AutoWorks.pdf
│
├── plantuml/
│   ├── arquitetura/
│   ├── casos-de-uso/
│   ├── classes/
│   ├── componentes/
│   ├── comunicacao/
│   ├── dados/
│   ├── estados/
│   ├── implantacao/
│   └── sequencia/
│
├── README.md
└── LICENSE
```

---

## 🛠 Ferramentas Utilizadas

| Ferramenta | Finalidade |
|------------|------------|
| **PlantUML** | Modelagem UML |
| **Draw.io** | Edição e exportação de diagramas |
| **Visual Studio Code** | Edição dos arquivos `.puml` |
| **Git & GitHub** | Controle de versão e hospedagem do projeto |
| **Markdown** | Documentação do repositório |

---

## 📖 Documentações Utilizadas

- 📘 PlantUML — https://plantuml.com
- 📘 C4-PlantUML — https://github.com/plantuml-stdlib/C4-PlantUML
- 📘 UML Resource Page — https://www.uml.org
- 📘 Draw.io — https://app.diagrams.net
- 📘 GitHub Docs — https://docs.github.com

---

## 👨‍💻 Autores

| Nome | GitHub |
|------|---------|
| **Bernardo Carvalho Denucci Mercado** | @bcarvalhom |
| **Equipe Orion AutoWorks** | Projeto acadêmico - Engenharia de Software |

---

## 🙏 Agradecimentos

- **PUC Minas** — pelo suporte institucional e incentivo às boas práticas de Engenharia de Software.
- **Disciplina Projeto de Software** — pela oportunidade de aplicar conceitos de análise, modelagem e arquitetura de sistemas.

---

## 📄 Licença

Este projeto possui finalidade exclusivamente **acadêmica e educacional**, sendo desenvolvido como atividade da disciplina **Projeto de Software** do curso de Engenharia de Software.

Distribuído sob a licença **MIT**. Consulte o arquivo `LICENSE` para mais informações.