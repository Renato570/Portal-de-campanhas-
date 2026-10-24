# Campanhas em Rede

Portal responsivo para reunir os sites das campanhas de saúde em um único endereço.

## Publicar na Vercel
1. Extraia o ZIP.
2. Envie `index.html` para um repositório GitHub novo, por exemplo `campanhas-em-rede`.
3. Na Vercel, importe esse repositório e faça o deploy.
4. O endereço gerado será o portal central.

## Atualizar o link do Outubro Rosa
No `index.html`, procure o cartão `Outubro Rosa` e substitua o link desabilitado pelo endereço publicado da campanha. Quando houver URL, retire a classe `disabled` do botão e remova `aria-disabled="true"` e `tabindex="-1"`.

Os cartões de campanhas futuras podem ser duplicados e ter título, descrição, cor e link alterados.
