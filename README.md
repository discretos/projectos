# Projectos

## Tabela de verdade

Uma tabela de verdade sumariza a combinação de duas ou mais condições lógicas baseadas nos operadores <code>AND</code>(disjunção), <code>OR</code>(conjunção) e <code>NOT</code>(negação). Em lógica, uma disjunção de duas proposições  é <b>verdadeira</b> se ambas as proposições forem <b>verdadeiras</b>. Se pelo menos uma das proposições é <b>verdadeira</b>, então
uma conjunção de duas proposições será <b>verdadeira</b>. A negação de uma proposição <b>verdadeira</b> é <b>falsa</b> e vice-versa. Finalmente a lei de DeMorgan diz-nos como fazer a negação de uma expressão booeleana (que toma valores <b>verdadeiros</b> ou <b>falsos</b>).

Neste projecto devemos implementar um sistema simples de geração de tabelas de verdade da uma expressão lógica. Por exemplo,
se for dada a entrada da seguinte expressão <code>a AND b</code> deverá ser produzida a seguinte tabela de verdade:

<br>
| a  | b  | a AND b  |
| -- | -- | -------- |
| 0  | 0  | 0        |
| 0  | 1  | 0 		 |
| 1  | 0  | 0        |
| 1  | 1  | 1        |

### Requisitos
* O sistema deve correr numa página web
* Implementar algumas operações de exemplo
* Utilizar ao máximo linguagens de cliente side (e.g: Javascript)
* Implementar mecanismos de validação de expressões bem formadas
*+ Implemetar um construtor de tabelas interativo (controi a tabela automaticamente mas que também constroí passo por passo)

### Observações
