# Mapa Operacional DGO — GCM Belo Horizonte

Aplicação web estática para visualização e organização de recursos operacionais.

## Recursos disponíveis

- mapa de Belo Horizonte;
- cadastro, edição e exclusão de recursos;
- movimentação direta das figuras;
- rotação e inversão horizontal;
- redimensionamento progressivo conforme o zoom;
- nomes visíveis;
- biblioteca com upload de imagens;
- modo claro, escuro e Modo Print;
- ajustes visuais salvos no Supabase.

## Publicação

O arquivo principal é `index.html`.

Para publicar pelo GitHub Pages, configure:

- Source: Deploy from a branch
- Branch: main
- Folder: /(root)

## Atenção

A configuração atual do Supabase foi escolhida para permitir leitura,
cadastro, edição, exclusão e upload sem login.

Isso significa que o endereço publicado não deve ser divulgado para pessoas
que não possam alterar os dados operacionais.
