\# Diagnóstico da base de dados



\*\*Fonte:\*\* Portal de Obras da Prefeitura de Itabaiana (PB)

https://portal.itabaiana.pb.gov.br/obras/



Base com 54 obras públicas, somando R$ 13,7 milhões em investimentos.



\## Problemas de qualidade encontrados



\### 1. Tipo de obra escrito de formas diferentes

\- \*\*O que encontrei:\*\* "PAVIMENTAÇÃO PARALELEPÍPEDO" e "PAVIMENTAÇÃO PARALEPÍPEDO" (erro de digitação).

\- \*\*Impacto na análise:\*\* nos gráficos por tipo, aparecem duas barras separadas para o mesmo tipo de obra, e a contagem de pavimentação fica dividida.

\- \*\*Como vou tratar:\*\* corrigir a grafia e unificar as duas categorias no Python, sem alterar a planilha original.



\### 2. Outros problemas

(Preencher durante a exploração dos dados no Python.)



\## Regras do painel



Para que os indicadores sejam confiáveis:

\- Todos os cards e gráficos respondem ao mesmo filtro de data, usando sempre a mesma coluna de data, e o período selecionado fica visível na tela.

\- Os gráficos identificam as categorias direto no eixo, sem depender só de cor e legenda.

\- A soma dos cards de situação deve ser igual ao total de obras, e isso é conferido com uma consulta de validação antes de publicar o painel.

