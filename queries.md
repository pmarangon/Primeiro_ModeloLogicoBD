SELECT sum(b.quantidade * b.precounitario) AS "Total Mensal"
FROM pedido a, produto b
WHERE MONTH (datemissao) = 01
AND b.idpedido = a.id