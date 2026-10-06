# Aconchego

Loja de roupas em página única (HTML, CSS e JavaScript, sem build).

## Publicar

1. Crie um repositório no GitHub e envie estes arquivos (`index.html` na raiz).
2. Na Vercel: **Add New → Project**, escolha o repositório e clique em **Deploy**.
   Framework: *Other*. Build command e output directory ficam em branco.
3. A cada commit na branch principal, a Vercel publica a versão nova.

## Atualizar produtos

Abra `https://seu-dominio/#gerenciar`. O painel cadastra, edita, esconde e exclui peças.
As alterações ficam só no seu navegador. Para publicar:

1. No painel, clique em **Baixar index.html**.
2. Substitua o `index.html` do repositório pelo arquivo baixado e faça o commit.
3. Depois que a Vercel publicar, clique em **Descartar alterações locais** no painel.

Visitantes que abrirem `#gerenciar` só editam a própria cópia no navegador deles.
Nada muda para os outros clientes.

## Importante

O pedido e o pagamento são simulados. Para vender de verdade é preciso ligar a uma
plataforma de e-commerce e a um meio de pagamento.
