# Board de Tarefas em Java

Projeto desenvolvido como parte do desafio da DIO para criar um **Board de Tarefas** em Java, seguindo boas práticas e arquitetura em camadas.

## Funcionalidades
- Criar tarefas
- Listar tarefas
- Atualizar tarefas
- Excluir tarefas
- Alterar status: **A Fazer → Em Andamento → Concluída**

## Arquitetura
- **Entidades/Model**
- **DAO/Repository** (acesso a dados)
- **Service** (regras de negócio)
- **UI/API** (interface de uso)
- **DTO** (transporte de dados entre camadas)

## Requisitos
- Java 17+  
- Maven ou Gradle (ver seção abaixo)
- IDE (VS Code ou IntelliJ)

## Como executar
1. Clone o repositório:
   ```bash
   git clone https://github.com/RechVictor/board-tarefas-java.git
   cd board-tarefas-java
