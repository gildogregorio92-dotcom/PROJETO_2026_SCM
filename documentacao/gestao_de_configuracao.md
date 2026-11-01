# Gestão de Configuração de Software

## 1. Conceito

Gestão de Configuração de Software é o conjunto de práticas utilizadas para identificar, organizar, controlar e acompanhar os artefatos produzidos durante o ciclo de vida de um software. Entre esses artefatos estão códigos-fonte, documentos, arquivos de configuração, roteiros de teste e modelos.

O controle de configuração ajuda a manter a integridade dos produtos de trabalho e permite saber o que foi alterado, quando a alteração ocorreu e qual versão está sendo utilizada.

## 2. Repositório de artefatos

Um repositório é um local centralizado ou distribuído onde os arquivos de um projeto são armazenados e versionados. Neste projeto, o Git é utilizado para controlar o histórico local e o GitHub hospeda uma cópia remota que pode ser compartilhada com colaboradores autorizados.

## 3. Controle de versões

O controle de versões registra alterações ao longo do tempo. Cada commit representa um conjunto de alterações acompanhado de uma mensagem descritiva. Com esse histórico, a equipe pode consultar versões anteriores, identificar a origem de mudanças e recuperar estados anteriores quando necessário.

## 4. Colaboração e integração

Em uma equipe, cada colaborador pode obter uma cópia do repositório, trabalhar em uma tarefa e enviar suas alterações. Em projetos com vários participantes, branches e pull requests ajudam a isolar mudanças e permitir revisão antes da integração à branch principal.

Quando duas alterações modificam trechos incompatíveis do mesmo arquivo, podem ocorrer conflitos. Esses conflitos precisam ser analisados e resolvidos antes de concluir a integração.

## 5. Benefícios

- Rastreabilidade das alterações.
- Histórico de versões.
- Redução do risco de sobrescrever trabalho de outras pessoas.
- Compartilhamento de artefatos atualizados.
- Apoio à revisão e à colaboração.
- Possibilidade de recuperar versões anteriores.

## 6. Aplicação neste projeto

O repositório PROJETO_2026_SCM organiza documentos explicativos e um registro de alterações. A estrutura permite demonstrar como artefatos podem ser armazenados e mantidos sob controle de versão. A comprovação da clonagem, edição local e envio deve ser feita por meio da execução prática dos comandos descritos em `procedimentos_git.md`.
