# Fluxo — MVP de gestão interna

MVP estático inspirado na organização visual de tarefas e Kanban do Huly, criado para uma agência pequena.

## Funcionalidades

- Clientes com cores e contatos
- Quadro Kanban por status
- Criar, editar e excluir atividades
- Arrastar cartões entre colunas
- Prioridade e prazo
- Comentários e atualizações por atividade
- Busca e filtros
- Tela de próximos prazos
- Persistência no `localStorage` do navegador

## Publicação

O pacote não exige build. Publique o conteúdo desta pasta como um site estático.

> Esta versão usa `localStorage`; cada navegador terá seus próprios dados. Para uso compartilhado, o próximo passo é conectar as mesmas telas ao Supabase com autenticação e banco PostgreSQL.

Os elementos foram implementados como uma interface nova, inspirada na arquitetura de tarefas do Huly. Não inclui nome, marca ou ativos proprietários do Huly.
