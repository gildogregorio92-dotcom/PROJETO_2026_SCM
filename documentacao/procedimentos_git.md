# Procedimentos de utilização do Git

Este documento apresenta os comandos necessários para obter o projeto, alterar um artefato e enviar a atualização ao GitHub.

## 1. Pré-requisitos

- Conta no GitHub.
- Git instalado: https://git-scm.com/downloads
- Acesso ao repositório: https://github.com/gildogregorio92-dotcom/PROJETO_2026_SCM

## 2. Configurar a identificação

Substitua os valores de exemplo pelos dados que deseja utilizar:

```bash
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@email.com"
```

## 3. Clonar o repositório

```bash
git clone https://github.com/gildogregorio92-dotcom/PROJETO_2026_SCM.git
cd PROJETO_2026_SCM
```

## 4. Verificar o estado dos arquivos

```bash
git status
```

## 5. Criar ou editar um artefato

Edite um dos documentos existentes ou crie um arquivo de texto na pasta do projeto. Por exemplo, acrescente uma nova entrada em `registro_alteracoes.txt`.

## 6. Preparar e registrar a alteração

```bash
git add .
git commit -m "Documenta alteracoes nos artefatos"
```

## 7. Enviar ao GitHub

```bash
git push origin main
```

Se o Git solicitar autenticação, siga o método de autenticação apresentado pelo GitHub. Não compartilhe senhas ou tokens.

## 8. Conferir o resultado

Acesse a página do repositório no GitHub e confirme se o arquivo alterado aparece com o conteúdo atualizado. Guarde capturas de tela do terminal e da página do repositório para anexar ao relatório.

> Os comandos deste documento são instruções para a execução local. A presença deste roteiro no repositório, por si só, não comprova que os comandos foram executados no computador.
