# BZtune — downloads oficiais

**Projeto:** BZtune Desktop para Windows.

Este repositório público será usado **somente para distribuir instaladores, notas de versão e atualizações assinadas** do BZtune. O desenvolvimento ocorre em um repositório separado e privado.

## Estado atual

> **Nenhum instalador Desktop foi publicado ainda.**
>
> A versão web está em desenvolvimento contínuo. Evite baixar executáveis apresentados por terceiros como se fossem releases oficiais.

## Onde baixar, quando estiver disponível

Acesse a seção [Releases](https://github.com/BadZ7br/BZtune-Releases/releases). A versão estável terá um instalador Windows e notas de versão; arquivos anexados precisam ser gerados pelo pipeline de build e testados antes da publicação.

## Como funcionará a atualização

A versão Desktop terá uma opção **Configurações → Sobre → Buscar atualizações**. O aplicativo consultará um feed HTTPS neste repositório e verificará a **assinatura criptográfica obrigatória** do Tauri Updater antes de instalar qualquer pacote.

Não é necessário criar conta nem fornecer token GitHub para baixar versões públicas. A publicação de novos releases depende de credenciais limitadas guardadas como segredos no processo de build do projeto privado — nunca dentro do programa.

## Privacidade e segurança

- **Músicas, banco SQLite, histórico e preferências do usuário não pertencem a este repositório**, nem serão enviados nos instaladores.
- **Nenhuma chave privada de assinatura** é publicada aqui.
- Atualizações são instaladas somente após confirmação do usuário.
- A função de atualizações ficará inativa até sua implementação e a publicação da primeira versão assinada.

## Desenvolvedor

[BZtune](https://github.com/BadZ7br/BZtune) · [Histórico de downloads](https://github.com/BadZ7br/BZtune-Releases/releases)
