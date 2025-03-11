# Sistema de Gerenciamento de Tarefas (Board)

## Sobre o Projeto
Este é um sistema de gerenciamento de tarefas (board) desenvolvido em Java, seguindo uma arquitetura em camadas. O projeto implementa um board de tarefas que permite organizar, acompanhar e gerenciar atividades de forma eficiente, similar a ferramentas como Trello ou Jira.

## Estrutura do Sistema

O projeto segue uma arquitetura em camadas:

1. **Camada de UI (Interface do Usuário)**
   - Interface para interação com o usuário
   - Apresentação de resultados de consultas
   - Tratamento de erros na interface

2. **Camada de Serviços**
   - Integração entre UI e acesso a dados
   - Tratamento de regras de negócio
   - Processamento de operações

3. **Camada de Acesso a Dados (DAO)**
   - Persistência e recuperação de informações
   - Consultas ao banco de dados
   - Gerenciamento de entidades

4. **Camada DTO (Data Transfer Objects)**
   - Objetos para transferência de dados entre camadas
   - Encapsulamento de dados para operações

5. **Camada de Persistência**
   - Armazenamento de dados
   - Gestão de migrations
   - Boas práticas de persistência

## Funcionalidades Implementadas

- Diagrama de solução para visualização da arquitetura
- Sistema de migrations para evolução do banco de dados
- Entidades e acesso a dados estruturados
- Consultas otimizadas para recuperação de informações
- Interface de usuário integrada com a camada de dados
- Tratamento de erros em diferentes níveis
- Blocos de update para modificação de dados
- Persistência de informações seguindo boas práticas

## Tecnologias Utilizadas

- Java (Backend)
- Gradle (Gerenciamento de dependências)
- Arquitetura em camadas (N-Tier)
- Sistema de migrations para banco de dados
- [Tecnologia de UI utilizada]

## Como Executar

1. Clone o repositório:
   ```
   git clone https://github.com/melissavalentindev/board-master.git
   ```

2. Navegue até o diretório do projeto:
   ```
   cd board-master
   ```

3. Compile o projeto com Gradle:
   ```
   ./gradlew build
   ```
   No Windows, use `gradlew.bat build`

4. Execute as migrations para criar a estrutura do banco de dados:
   ```
   ./gradlew migrate
   ```

5. Execute a aplicação:
   ```
   ./gradlew run
   ```

## Desenvolvimento

O projeto foi desenvolvido seguindo estas etapas:

1. Setup inicial do projeto
2. Criação do diagrama de solução
3. Implementação de migrations para o banco de dados
4. Desenvolvimento de entidades e acesso a dados
5. Criação da camada de acesso a dados
6. Desenvolvimento da interface de usuário
7. Integração entre UI e acesso aos dados
8. Implementação da camada de serviços
9. Refinamento da camada DAO
10. Otimização de consultas
11. Exibição de resultados na UI
12. Tratamento de erros
13. Implementação da camada DTO
14. Aplicação de boas práticas na camada de persistência
15. Criação de blocos de update
