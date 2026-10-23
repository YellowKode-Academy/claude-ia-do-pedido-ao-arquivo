---
name: relatorio-de-vendas
description: Gera o relatório mensal de royalties da editora a partir do extrato em CSV. Use quando eu pedir "relatório de vendas", "como foi o mês" ou anexar o extrato de royalties.
---

# Relatório de vendas

## Quando usar
Quando eu anexar o extrato de royalties (colunas: mes, loja, moeda, royalty_ebook, royalty_kindle_unlimited_ou_paginas, kenp_ja_pago) e pedir o relatório.

## Passos
1. Some só as linhas em BRL. As outras moedas vão numa linha à parte, "outras lojas", com o valor original de cada uma, sem converter.
2. Na coluna de Kindle Unlimited, use como dinheiro apenas as linhas com kenp_ja_pago = true. As linhas com "páginas" não são dinheiro: mostre só o número de páginas, num item "a receber".
3. Monte uma tabela por mês com: ebook (R$), Kindle Unlimited pago (R$) e total (R$).
4. Diga qual foi o melhor mês e o pior mês, e compare o último mês com o anterior em porcentagem.
5. Escreva no máximo 3 frases de conclusão. Nenhuma recomendação: isso eu decido.

## Formato da entrega
Título "Relatório de vendas: [mês do último dado]", a tabela, a linha "outras lojas", o item "a receber" e as 3 frases.

## Conferência (sempre, no fim)
Mostre a soma do total do ano feita linha a linha, para eu refazer na calculadora.

## Nunca
- Converter moeda estrangeira por cotação que você supôs.
- Tratar páginas lidas como dinheiro.
- Arredondar valores da tabela.
