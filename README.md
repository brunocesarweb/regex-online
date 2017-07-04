# Regex-Online
A builded simple page for regex search, developed by Alura.

##Quantifier:

{n} - exatamente n vezes.
{n, } - no mínimo n vezes.
{n,m} - no mínimo n, no máximo m vezes.

? - zero ou mais vez.
+ - uma ou mais vezes.
* - zero ou mais vezes.

##Classes de char - []

[A-Z] - letras de A até Z
[123] - 1,2 ou 3
\d - todos os dígitos
\s - whitespace [ \t\r\n\f]
\w - wordchar [A-Za-z0-9_]

##Exemplos de classes e quantifiers aplicados:

[A-Z] [a-zç] {3,8} - mês
[1-3]?\d - dia
\d{3} - 3 dígitos
\s+ - um ou mais whitespaces

##Word char
[A-Za-z0-9_] - selecionar caracteres

##Word boundary

\bpalavra\b
