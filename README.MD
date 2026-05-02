# Sistema de Chamados Técnicos

## 📌 Descrição

Projeto acadêmico desenvolvido para a disciplina de Práticas Extensionistas III, com o objetivo de modelar um **Sistema de Chamados Técnicos** para registro, acompanhamento e gerenciamento de solicitações de suporte.

O sistema permite que clientes abram chamados técnicos, enquanto técnicos e administradores acompanham, atualizam e finalizam atendimentos.

---

## 🎯 Objetivo do Projeto

Desenvolver a modelagem conceitual e lógica de um sistema de informação, aplicando conceitos de:

* Modelagem Entidade-Relacionamento
* UML
* Engenharia de Software
* Banco de Dados
* Documentação técnica

---

## 👥 Integrantes

* Kauan Natanael de Oliveira
* Kévin Brayan dos Santos Teixeira

---

## 🛠️ Ferramentas Utilizadas

* BRModelo
* Visual Paradigm Community Edition
* GitHub

---

## 📚 Funcionalidades do Sistema

### Cliente

* Realizar login
* Abrir chamado
* Consultar chamados
* Acompanhar status
* Adicionar comentários

### Técnico

* Visualizar chamados
* Assumir atendimento
* Atualizar status
* Registrar comentários
* Encerrar chamado

### Administrador

* Gerenciar usuários
* Gerenciar categorias
* Consultar chamados

---

## 🗂️ Estrutura do Projeto

```text
/projeto
 ├── README.md
 ├── docs/
 │   ├── MER_Conceitual.png
 │   ├── MER_Logico.png
 │   ├── Diagrama_Classes.png
 │   ├── Caso_de_Uso.png
 │   ├── Sequencia_Abertura.png
 │   ├── Sequencia_Atendimento.png
 │   ├── Atividade_Abertura.png
 │   └── Atividade_Atendimento.png
 └── entrega.pdf
```

---

## 🧩 Diagramas Desenvolvidos

### Banco de Dados

* Modelo Entidade-Relacionamento Conceitual
* Modelo Entidade-Relacionamento Lógico

### UML

* Diagrama de Classes
* Diagrama de Caso de Uso Geral
* Diagrama de Sequência – Abertura de Chamado
* Diagrama de Sequência – Atendimento de Chamado
* Diagrama de Atividade – Abrir Chamado
* Diagrama de Atividade – Atender/Encerrar Chamado

---

## 📌 Regras de Negócio

* Um cliente pode abrir vários chamados.
* Cada chamado pertence a um cliente.
* Um técnico pode atender vários chamados.
* Chamados possuem prioridade e status.
* Um chamado pode conter comentários/histórico.

---

## 📄 Licença

Projeto acadêmico sem fins comerciais.
