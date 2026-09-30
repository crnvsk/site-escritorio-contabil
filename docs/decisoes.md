# Diário de Decisões

## 001 - Nome do Repositório

- **Data:** 29/09/2026
- **Contexto:** Preciso definir o nome do repositório do projeto.
- **Decisão:** site-escritorio-contabil
- **Motivo:** Nome descritivo e curto, demonstrando do que o projeto trata.

## 002 - Visibilidade e licença

- **Data:** 29/09/2026
- **Contexto:** Preciso definir a visibilidade do repositório e o tipo de licença utilizada.
- **Decisão:** Público e MIT license.
- **Alternativas:** Privado e sem licença.
- **Motivo:** Público, para o projeto servir de portfólio e MIT license, por ser a mais simples e funcional.

## 003 - Template do .gitignore

- **Data:** 29/09/2026
- **Contexto:** Preciso definir o template do .gitignore do projeto.
- **Decisão:** Usar o padrão Node.
- **Alternativas:** Nenhum template ou criar manualmente.
- **Motivo:** Provisório, mas já vem pré-configurado de uma forma que funciona para o projeto e provavelmente para a stack que será utilizada, já que impede que arquivos desnecessários ou sensíveis vão para o repositório.

## 004 - Autenticação com o GitHub via SSH

- **Data:** 29/09/2026
- **Contexto:** Preciso autenticar no GitHub para enviar commits.
- **Decisão:** Usar chave SSH (ed25519), sem passphrase.
- **Alternativas:** HTTPS com token ou gerenciador de credenciais.
- **Motivo:** Configuro uma vez e vale para todos os repositórios. Sem passphrase por ser uma máquina pessoal, aceitando o risco se alguém tiver acesso ao computador.

## 005 - Padrão de mensagens de commits

- **Data:** 29/09/2026
- **Contexto:** Preciso definir como será o padrão das minhas mensagens de commits.
- **Decisão:** Usar conventional commits e Português-BR.
- **Alternativas:** Mensanges livres sem padrão, Inglês-US.
- **Motivo:** Conventional commits, para melhor organização de cada mudança e Português, porque meu foco atual é o mercado brasileiro e quero que possíveis recrutadores consigam entender com mais facilidade.
